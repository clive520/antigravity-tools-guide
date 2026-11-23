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
  - 30+ 款底層 MCP API 參考表、實務對話 Prompt 範本與進階設定。

---

## 📁 檔案結構

```tree
antigravity-tools-guide/
├── index.html           # 導覽首頁：模組化字卡網格系統
├── chrome-devtools.html # Chrome DevTools MCP 詳細教學指南
├── .nojekyll            # 確保 GitHub Pages 靜態檔案正常運作
└── README.md            # 專案說明文件
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
