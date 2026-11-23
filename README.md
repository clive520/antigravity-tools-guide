# Antigravity 擴充工具庫指南 (Antigravity Tools Hub)

> 一站式探索與掌握 AI Agent 必備外掛、MCP 協議與自動化工具知識庫。

🌐 **線上即時預覽 (GitHub Pages)**: [https://clive520.github.io/antigravity-tools-guide/](https://clive520.github.io/antigravity-tools-guide/)

---

## 📖 專案簡介

本專案收錄並整理 Antigravity 2.0 擴充套件市場（Marketplace）中官方與合作夥伴提供的關鍵工具使用指南，旨在幫助開發者、教育工作者、設計師、數據分析師與各領域專業人士充分發揮 AI Agent 的自動化、雲端協作與視覺生產力。

目前已全面完成收錄 **Google 家族（Google Family）全系列核心服務** 與 **Canva AI 視覺設計旗艦生態**，共計 9 大專題頁面與 90 組以上跨角色實戰 Prompt。

---

## 🌟 收錄專題與指南矩陣

### 1. 核心首頁與導航 (`index.html`)
- **模組化高擴充性字卡網格（Card Grid）**：支援即時關鍵字模糊搜尋、多類別標籤過濾（全部、Google 家族、除錯與效能、瀏覽器與自動化、創意設計與簡報）。
- **完整導覽連結**：一鍵直達各工具專屬手冊，並具備優雅的暗黑毛玻璃（Dark Tech Glassmorphism）現代科技美學。

### 2. Chrome DevTools MCP (`chrome-devtools.html`)
- **官方維護版本**：由 Chrome DevTools 官方團隊維護的 MCP 擴充套件完整解析（v1.10.1）。
- **六大專屬指令**：`/chrome-devtools`、`/debug-optimize-lcp`、`/cookie-debugging`、`/memory-leak-debugging`、`/a11y-debugging`、`/troubleshooting`。
- **10 大跨角色實戰範例**：涵蓋前端工程師、QA 自動化測試、SRE 效能工程師、全端 API 排錯、資安審查、無障礙專員、SEO 顧問等。

### 3. Google Drive & Docs (`google-drive-docs.html`) · Google 家族首推
- **雙外掛整合**：`antigravity-plugins-official/plugin/gdrive` 與 `plugin/gdocs`。
- **核心能力**：雲端硬碟全文檢索、AI 文件排版撰寫、修訂批註管理與跨組織協作權限分享。
- **10 大跨角色實戰範例**：涵蓋教師備課教案、文史田野調查、軟體架構決策 (ADR)、產品需求文件 (PRD)、主管 OKR 彙報等。

### 4. Google Sheets (`google-sheets.html`) · Google 家族二棒
- **試算表與數據分析**：`antigravity-plugins-official/plugin/gsheets`。
- **核心能力**：百萬儲存格批次讀寫、髒資料清洗正規化、高階 QUERY / XLOOKUP / ARRAYFORMULA 函數生成與條件格式警示熱圖。
- **隨附 10 組 UTF-8 BOM 實戰 CSV 檔案**：提供使用者直接下載上傳，涵蓋成績加權、電商 ROAS、財務報銷、人資考勤、Scrum 燃盡圖等真實資料集。

### 5. Gmail & Google Calendar (`gmail-calendar.html`) · Google 家族三棒
- **個人秘書中樞**：`antigravity-plugins-official/plugin/gmail` 與 `plugin/gcalendar`。
- **核心能力**：晨間未讀摘要、情境商務回信草稿、跨時區空檔查詢、自動預約會議附帶 Google Meet 視訊與生活帳單/機票提醒防呆入曆。
- **10 大跨角色實戰範例**：涵蓋總裁特助晨報、跨國業務排程、專案里程碑 Review、親師懇談約訪、HR 面試官協調等。

### 6. Google Slides (`google-slides.html`) · Google 家族四棒
- **視覺簡報與演講生成**：`antigravity-plugins-official/plugin/gslides`。
- **核心能力**：SOIL 全科教學簡報六引擎架構、商業路演 Pitch Deck 排版、圖表自動生成與講者備忘稿 (Speaker Notes) 同步撰寫。
- **10 大跨角色實戰範例**：涵蓋跨領域專案教師、新創創辦人、企業內訓講師、學術研討會學者、產品經理 Roadmap 簡報等。

### 7. Google NotebookLM (`google-notebooklm.html`) · Google 家族五棒
- **學術與文獻深度研究**：`gemini-notebook-mcp`。
- **核心能力**：多源文獻錨定 (Source Grounding)、精確註腳反查、跨來源語義搜尋、以及 Studio 雙主持人 AI 語音播客 (Audio Overview) 一鍵生成。
- **10 大跨角色實戰範例**：涵蓋碩博士論文文獻探討、醫學指引比較、智財專利迴避分析、法規合規審查、Podcast 劇本生成等。

### 8. Firebase (`firebase.html`) · Google 家族六棒
- **全端後端與雲端基礎設施**：`antigravity-plugins-official/plugin/firebase`。
- **核心能力**：Firestore NoSQL 關聯設計、Firebase Hosting 一鍵全球 CDN 部署、Firebase Auth 安全驗證與 Security Rules 安全規則防呆審計。
- **10 大跨角色實戰範例**：涵蓋全端 Web 開發者、資安稽核員、行動 App 後端工程師、無伺服器微服務部署、Staging 快速預覽預發布等。

### 9. Google Cloud & Gemini Developer (`google-cloud-gemini.html`) · Google 家族七棒旗艦
- **旗艦全生態整合**：`gemini-api`、`google-cloud-developer` 與 `data-agent-kit-plugin`。
- **核心能力**：Gemini 2.0 Flash / 1.5 Pro 百萬 Token 多模態上下文 API、Cloud Run 容器無伺服器藍綠部署、BigQuery TB 級資料庫 Dry-Run 優化查詢與 FinOps 成本資安防線。
- **10 大跨角色實戰範例**：涵蓋全端 AI 工程師、雲端 SRE 維運工程師、企業數據分析師、FinOps 審計師、資安架構師、資料管線工程師等。

### 10. Canva AI 視覺設計與行銷自動化 (`canva.html`) · 設計生態旗艦
- **官方生態整合**：`canva_canva` 原生 MCP 伺服器、7 大專屬 Skills 與 Canva CLI (`canva api`)。
- **核心能力**：CSV/JSON 表格批次套印大量海報 (Bulk Create)、社群全通路尺寸重構 (Smart Resize)、AI 前景去背與多圖層分離 (Separate Layers)、品牌規範自動核查 (Brand Checker) 與協同審閱評論自動實裝修改。
- **10 大跨角色實戰範例**：涵蓋社群行銷經理、電商營運企劃、品牌識別總監、UI/UX 設計師、學校培訓教師、多語在地化專員、自由接案設計師、活動策展人、DevOps 自動化工程師等。

---

## 📁 檔案結構

```tree
antigravity-tools-guide/
├── index.html                   # 導覽首頁：模組化字卡網格系統 (收錄 9 大專題)
├── chrome-devtools.html         # Chrome DevTools MCP 詳細教學指南
├── google-drive-docs.html       # Google Drive & Docs 完整使用指南
├── google-sheets.html           # Google Sheets 試算表與數據分析指南
├── gmail-calendar.html          # Gmail & Google Calendar 個人 AI 秘書指南
├── google-slides.html           # Google Slides 視覺簡報與 SOIL 架構指南
├── google-notebooklm.html       # Google NotebookLM 深度研究與播客生成指南
├── firebase.html                # Firebase 全端後端與 Security Rules 指南
├── google-cloud-gemini.html     # Google Cloud & Gemini Developer 旗艦指南
├── canva.html                   # Canva AI 視覺設計與行銷自動化指南
├── data/
│   └── sheets/                  # 10 組情境擬真 UTF-8 BOM 練習用 CSV 資料檔
├── .nojekyll                    # 確保 GitHub Pages 靜態檔案正常運作
└── README.md                    # 專案說明文件
```

---

## 🛠️ 如何新增更多工具字卡？

首頁設計採用標準 Tailwind CSS 與資料屬性（Data Attributes），若要新增工具：
1. 複製 `index.html` 中的卡片區塊 `<div class="tool-card glass-card ...">`。
2. 修改 `data-category` 與 `data-title` 以支援即時分類與搜尋。
3. 建立對應的詳細頁面（如 `canva.html`）並在卡片中更新超連結。

---

## 👤 作者與維護
- 建立者：[clive520](https://github.com/clive520)
- 平台：Antigravity 2.0 & Google DeepMind Agentic AI
- 授權：MIT License
