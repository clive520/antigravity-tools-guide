# 【Antigravity 擴充工具庫指南】本機軟體第 4 棒：Unity Editor MCP 實戰指南開發計畫書

- **專案代號**：`DESKTOP-MCP-04-UNITY`
- **負責工具**：Unity Editor (全球普及度第一的跨平台遊戲引擎)
- **對應頁面**：`unity.html`
- **首頁卡片**：Card 24 (`index.html`)
- **建立日期**：2026-11-24
- **當前版本**：v1.0.0 (核准實裝)

---

## 一、專案背景與整合價值

### 1.1 為什麼將 Unity Editor 列為本機軟體第四棒？
Unity 是全球獨立遊戲開發者 (Indie Game Dev)、手遊工作室與 XR 互動展演最廣泛使用的遊戲引擎。

傳統在 Unity 中開發，開發者必須在代碼編輯器（VS Code / Visual Studio）與 Unity 編輯器介面之間來回切換、手動建立 Prefab、拖曳掛載組件並在 Inspector 中調整參數。
透過 Unity MCP 橋接：
1. **編輯器層級的自動化編排**：AI 代理能直接透過 MCP 在 Hierarchy 中生成 GameObject、調整 Transform 座標與旋轉、掛載 Rigidbody / Collider / AudioSource，並一鍵套用 Material。
2. **自動化測試與 Console 錯誤自愈**：AI 可直接執行 Unity Test Framework 單元測試、讀取 Editor Console 錯誤日誌與 Warning，甚至直接修復出錯的 C# 代碼並重新編譯。
3. **場景搭建高效率推進**：透過自然語言提示詞，數秒內搭建包含相機、主光源、地形地面與物理障礙物的完整遊戲 Prototype。

---

## 二、使用者基本條件與環境需求 (User Prerequisites)

| 項目類別 | 規格與基本條件 | 說明與備註 |
| :--- | :--- | :--- |
| **軟體主程式** | **Unity 2021 LTS、2022 LTS 或 Unity 6+** | 個人版 (Personal) 完全免費。 |
| **外掛與執行環境** | 本機 Unity 擴充套件（`unity-mcp` 或 `MCPBridge.cs`）+ Node.js 18+ | 透過 WebSocket 伺服器與 Unity Editor 通訊。 |
| **硬體規格** | 建議 16GB+ RAM，具備獨立顯卡（NVIDIA / AMD / Apple Silicon） | 保證 3D 場景即時烘焙與 Play-In-Editor (PIE) 流暢運行。 |
| **AI 客戶端** | Antigravity 2.0、Cursor、Claude Desktop 或 VS Code | 具備多模態視覺模型可分析 Game View 截圖與 UI 介面排版。 |
| **網路與通訊安全** | 本機內部 WebSocket 通訊埠 `127.0.0.1:8080` | 本機沙盒封閉，無遠端入侵風險。 |
| **技能門檻** | **新手～資深遊戲開發者皆宜** | 初學者可用自然語言生成場景，資深工程師可用於自動化管線與除錯。 |

---

## 三、系統架構與技術通訊協議

```mermaid
flowchart LR
    Agent["AI Agent<br>(Claude / Cursor / Antigravity)"] -->|stdio JSON-RPC| MCP["Unity MCP Server<br>(Node.js Bridge)"]
    MCP -->|WebSocket (127.0.0.1:8080)| Plugin["Unity Editor Plugin<br>(MCPBridge.cs / C# API)"]
    Plugin -->|UnityEditor & UnityEngine API| Engine["Unity 編輯器核心<br>(Hierarchy / Inspector / Console)"]
    Engine -->|Console 日誌 / 測試結果 / GameView 截圖| Agent
```

---

## 四、核心工具架構（5 大核心工具）

1. `unity_create_gameobject`: 建立物件、設定父子階層 (Parent/Child) 與 Transform 座標縮放。
2. `unity_set_component_property`: 掛載組件（如 BoxCollider, Light, NavMeshAgent）並修改數值。
3. `unity_get_scene_hierarchy`: 抓取當前開放場景內所有 GameObject 階層樹與激活狀態。
4. `unity_run_tests_and_get_logs`: 執行 PlayMode / EditMode 測試並抓取 Console 紅字報錯。
5. `unity_execute_menu_item`: 執行 Unity 編輯器頂部功能表命令（如 Asset Refresh, Build, Save Scene）。

---

## 五、10 大跨角色實戰 Prompt 設計
1. **獨立遊戲程式員**：建立 3D 角色控制器 Prototype（膠囊體 + 剛體 + 角色移動腳本掛載）。
2. **關卡設計師 (Level Designer)**：隨機生成 20 個帶碰撞體的箱形障礙物，並自動烘焙 NavMesh 尋路網格。
3. **遊戲音效程式員**：遍歷場景中所有敵人 Prefab，批次掛載 3D 空間音效 AudioSource 與衰減曲線。
4. **遊戲 UI/UX 架構師**：自動建立 Canvas 視窗，加入血條 Slider、計分 TextMeshPro 與暫停選單。
5. **物理模擬工程師**：搭建骨牌多米諾連鎖碰撞物理實驗場景，精準計算質量與摩擦力。
6. **遊戲 QA 自動化測試員**：批次執行玩家存檔與道具背包單元測試，抓取 NullReferenceException 報錯堆疊。
7. **著色器與 VFX 美術師**：建立帶點光源 (Point Light) 的炫光粒子系統 (Particle System) 爆炸特效。
8. **多語在地化專員**：掃描場景中所有 TextMeshPro 元件，將中文字符串替換為多語 Localization Key。
9. **VR/AR 互動工程師**：快速配置 XR Origin 追蹤相機與雙手射線 Raycast 交互控制器。
10. **AI 遊戲場景自檢架構師**：檢視 Hierarchy 物件層級，自動清除懸空的孤兒 GameObject 與遺失腳本 (Missing Scripts)。

---

## 六、頁面視覺規範
- 主題色彩：Unity 鋼鐵冷灰 (`#334155`) 搭配科技翡翠綠 (`#10b981` / `emerald-500`)。
- 交付檔案：`unity.html`、`index.html` (Card 24)。
