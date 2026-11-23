# Antigravity 擴充工具庫指南 (Antigravity Tools Hub)

> 一站式探索與掌握 AI Agent 必備外掛、MCP 協議與自動化工具知識庫。

🌐 **線上即時預覽 (GitHub Pages)**: [https://clive520.github.io/antigravity-tools-guide/](https://clive520.github.io/antigravity-tools-guide/)

---

## 📖 專案簡介

本專案收錄並整理 Antigravity 2.0 擴充套件市場（Marketplace）中官方與合作夥伴提供的關鍵工具使用指南，旨在幫助開發者與使用者充分發揮 AI Agent 的自動化與工程除錯能力。

### 🌟 架構特點
- **模組化高擴充性首頁 (`index.html`)**：
  - 具備即時關鍵字搜尋與分類標籤過濾（全部、除錯效能、瀏覽器自動化、創意設計）。
  - 卡片網格（Card Grid）架構，可隨時追加新的工具字卡，連結至各自專屬的說明子頁面。
- **Chrome DevTools MCP 專屬指南 (`chrome-devtools.html`)**：
  - 由 Chrome DevTools 官方團隊維護的 MCP 擴充套件完整解析（v1.10.1）。
  - 六大內建指令（Slash Commands）深度解析：`/chrome-devtools`、`/debug-optimize-lcp`、`/cookie-debugging`、`/memory-leak-debugging`、`/a11y-debugging`、`/troubleshooting`。
  - **10 大跨角色實戰應用範例**：涵蓋前端工程師、QA 測試、SRE 效能工程師、全端 API 排錯、資安審查、前端架構師、無障礙專員、SEO 顧問、Chrome Extension 開發者與客服技術維運。
  - 30+ 款底層 MCP API 參考表、實務對話 Prompt 範本與進階設定。
- **Google Drive & Docs 官方指南 (`google-drive-docs.html`)**：
  - Google 官方原生 Workspace 雙外掛 (`gdrive` + `gdocs`) 深度解析。
  - 雲端硬碟全文檢索、自動撰寫排版 Google 文件、多版本修訂與跨團隊共享。
  - **10 大跨角色實戰應用範例**：涵蓋教師備課教案、文史田野調查、軟體工程 ADR、產品經理 PRD、專案會議紀錄、行銷文案、合約審查、主管 OKR 彙報、客服 SOP 與學生考前衝刺筆記。
  - OAuth 2.0 授權綁定與常見問題 (FAQ)。
- **Google Sheets 官方指南 (`google-sheets.html`)**：
  - Google 官方原生試算表外掛 (`gsheets`) 深度解析。
  - 結構化大數據讀寫、資料清洗去重、自動生成高階函數（QUERY / XLOOKUP / ARRAYFORMULA）、條件格式警示熱圖與跨分頁樞紐分析。
  - **10 大跨角色實戰應用範例（隨附 10 組真實練習 CSV 資料集）**：涵蓋導師成績加權排行、電商 ROAS 監控、財務報銷核銷、人資出勤異常核對、Scrum 燃盡圖、庫存安全存量預警、活動問卷電話正規化、業務階梯獎金試算、實驗室離群值篩除與個人外匯記帳。
  - 4 大神級公式解析與常見問答。
- **Gmail & Google Calendar 官方指南 (`gmail-calendar.html`)**：
  - Google 官方原生秘書雙外掛 (`gmail` + `gcalendar`) 深度解析。
  - 晨間未讀要事篩選、專業回信草稿暫存、跨時區空檔查詢、自動建立會議附帶 Google Meet 視訊與生活帳單/機票提醒防呆入曆。
  - **10 大跨角色實戰應用範例**：涵蓋總裁特助晨報、跨國業務時差排程、專案里程碑 Review、導師親師懇談約訪、HR 多面試官排程、客服緊急案件回信、顧問預約與調研、年會講者邀請、研究生頂會錄取追蹤與個人帳單機票防呆。
  - 草稿模式優先安全機制與權限設定。

---

## 📁 檔案結構

```tree
antigravity-tools-guide/
├── index.html              # 導覽首頁：模組化字卡網格系統
├── chrome-devtools.html    # Chrome DevTools MCP 詳細教學指南
├── google-drive-docs.html  # Google Drive & Docs 完整使用指南
├── google-sheets.html      # Google Sheets 試算表與數據分析指南 (含 10 組 CSV 下載)
├── gmail-calendar.html     # Gmail & Google Calendar 個人 AI 秘書指南
├── data/
│   └── sheets/             # 10 組情境擬真 UTF-8 BOM 練習用 CSV 資料檔
├── .nojekyll               # 確保 GitHub Pages 靜態檔案正常運作
└── README.md               # 專案說明文件
```

---

## 🛠️ 如何新增更多工具字卡？

首頁設計採用標準 Tailwind CSS 與資料屬性（Data Attributes），若要新增工具：
1. 複製 `index.html` 中的卡片區塊 `<div class="tool-card glass-card ...">`。
2. 修改 `data-category` 與 `data-title` 以支援即時分類與搜尋。
3. 建立對應的詳細頁面（如 `canva-mcp.html`）並在卡片中更新超連結。

---

## 👤 作者與維護
- 建立者：[clive520](https://github.com/clive520)
- 平台：Antigravity 2.0 & Google DeepMind Agentic AI
