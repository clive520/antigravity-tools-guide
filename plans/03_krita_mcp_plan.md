# 【Antigravity 擴充工具庫指南】本機軟體第 3 棒：Krita MCP 實戰指南開發計畫書

- **專案代號**：`DESKTOP-MCP-03-KRITA`
- **負責工具**：Krita (開源專業 2D 數位插畫與繪圖軟體)
- **對應頁面**：`krita.html`
- **首頁卡片**：Card 23 (`index.html`)
- **建立日期**：2026-11-24
- **當前版本**：v1.0.0 (核准實裝)

---

## 一、專案背景與整合價值

### 1.1 為什麼將 Krita 列為本機軟體第三棒？
Krita 是自由與開源軟體基金會 (KDE) 旗下享譽全球的專業數位插畫與概念美術繪圖軟體，深受插畫家、漫畫家、遊戲原畫師與動畫師喜愛。

透過 MCP 與 Krita 原生 Python Plugin 橋接：
1. **多模態「看圖－繪圖－修圖」閉環**：Krita MCP 具備最吸引人的特點——AI 可命令筆刷在畫布上鋪底色或繪製線稿，調用畫布快照（Canvas Screenshot）以 Base64 PNG 回傳給多模態視覺模型（Claude 3.5 / Gemini 2.0），讓 AI 審視色調對比、輪廓比例並自主調色修線。
2. **圖層與混合模式自動編排**：支援自動建立「線稿層」、「固有色層」、「陰影遮罩層」與「光影高光層」，並設定 Normal / Multiply / Overlay 等混合模式。
3. **完全開源零版權負擔**：免除任何付費授權，在地端無限制發揮生成式繪圖協作。

---

## 二、使用者基本條件與環境需求 (User Prerequisites)

| 項目類別 | 規格與基本條件 | 說明與備註 |
| :--- | :--- | :--- |
| **軟體主程式** | **Krita 5.1 或 5.2+**（推薦官方最新穩定版） | 官方免費開源，支援 Windows、macOS 與 Linux。 |
| **外掛與執行環境** | 本機 Krita Python Plugin（`krita-mcp`）+ Python 3.10+ / FastMCP | 在 Krita「設定 ➔ 配置 Krita ➔ Python 外掛程式管理員」中啟用。 |
| **硬體規格** | 建議 8GB+ RAM（多圖層高解析度 300DPI 畫布推薦 16GB RAM） | 支援 OpenGL 3.2 畫布平滑旋轉與硬體縮放。 |
| **AI 客戶端** | Antigravity 2.0、Claude Desktop、Cursor 等 | **強烈推薦具備 Vision 視覺理解能力之 LLM**，以實現畫布視覺回饋閉環。 |
| **網路與通訊安全** | 本機環回位址 `127.0.0.1:8080` (FastMCP HTTP / Socket) | 僅限本機通訊，保護使用者數位畫布隱私。 |
| **技能門檻** | **零繪圖技術門檻** | 自然語言描述畫面氛圍、構圖與角色特徵，由 AI 執行圖層建構與筆刷佈局。 |

---

## 三、系統架構與技術通訊協議

```mermaid
flowchart LR
    Agent["AI Agent<br>(Claude / Gemini)"] -->|stdio JSON-RPC| MCP["Krita FastMCP Server"]
    MCP -->|本機 HTTP/Socket (127.0.0.1:8080)| Plugin["Krita Python Plugin (內建伺服器)"]
    Plugin -->|Krita Python API| Engine["Krita 核心畫布 (Canvas / Layers / Brushes)"]
    Engine -->|畫布即時快照 PNG| Agent
```

---

## 四、核心工具架構（5 大核心工具）

1. `krita_create_document`: 建立指定解析度（如 3840x2160, 300DPI, RGB 8-bit）的新畫布。
2. `krita_layer_management`: 建立、命名、刪除圖層，調整不透明度 (Opacity) 與圖層混合模式 (Blending Mode)。
3. `krita_draw_stroke_shape`: 使用指定色彩、筆刷形狀與座標繪製色塊、線條或漸層。
4. `krita_get_canvas_screenshot`: 擷取當前圖層或合併畫布之即時 PNG 快照回傳給 AI 模型審視。
5. `krita_export_image`: 匯出畫布為 `.kra`（工程檔）、`.png` 或 `.psd` 格式。

---

## 五、10 大跨角色實戰 Prompt 設計
1. **概念場景原畫師**：建立賽博朋克夜雨街景色彩基調（藍紫高對比底色 + 霓虹倒影圖層）。
2. **動漫角色線稿師**：自動建立三層標準結構（草稿藍線層、純黑精修線稿層、純色遮罩底層）。
3. **遊戲 2D 像素美術**：建立 64x64 畫布與專屬調色盤，繪製復古 RPG 地牢寶箱動畫幀。
4. **水彩風格插畫家**：配置紙張紋理圖層（Multiply 混合模式），繪製柔和邊緣暈染靜物。
5. **童書繪本繪師**：暖色系大色塊森林背景排版，預留中央文字安全閱讀區域。
6. **UI 圖示設計師**：300DPI 網格對齊繪製 8 款扁平科技風格幾何 App 圖標。
7. **啞光背景 (Matte Painter)**：建立遠景雪山與中景雲海的多重深度圖層並設定大氣透視霧效。
8. **刺青紋身設計師**：極細單色線條繪製幾何曼陀羅圖騰，並建立對稱鏡像輔助軸線。
9. **材質貼圖 (Texture Artist)**：生成 2048x2048 無縫平鋪的粗糙磚牆紋理與法線圖層。
10. **AI 畫布自我審查藝術總監**：截取畫布檢測焦點人物與背景明暗對比，動態調整陰影圖層不透明度。

---

## 六、頁面視覺規範
- 主題色彩：數位繪藝洋紅粉紫 (`#ec4899` / `pink-500`、`#a855f7` / `purple-500`)。
- 交付檔案：`krita.html`、`index.html` (Card 23)。
