# Antigravity 擴充工具庫指南 (Antigravity Tools Hub)

> 一站式探索與掌握 AI Agent 必備外掛、MCP 協議與自動化工具知識庫。

🌐 **線上即時預覽 (GitHub Pages)**: [https://clive520.github.io/antigravity-tools-guide/](https://clive520.github.io/antigravity-tools-guide/)

---

## 📖 專案簡介

本專案收錄並整理 Antigravity 2.0 擴充套件市場（Marketplace）中官方與合作夥伴提供的關鍵工具使用指南，旨在幫助開發者、教育工作者、設計師、數據分析師與各領域專業人士充分發揮 AI Agent 的自動化、雲端協作與視覺生產力。

目前已全面完成收錄 **Chrome DevTools**、**Google 家族（Google Family）全系列核心服務**、**Canva AI 視覺設計旗艦生態**、**開發者自動化前五棒（GitHub CLI、Figma、Notion、n8n、Supabase）**、**擴充第 6～10 棒（Cloudflare、Stripe、Linear、Atlassian TWG、invideo）**，以及**本機軟體創作第十一棒（Blender 3D MCP）**，共計 20 大專題頁面與 200 組以上跨角色實戰 Prompt。

---

## 🌟 收錄專題與指南矩陣

### 1. 核心首頁與導航 (`index.html`)
- **模組化高擴充性字卡網格（Card Grid）**：支援即時關鍵字模糊搜尋、多類別標籤過濾（全部、辦公協作與知識庫、後端與除錯、自動化與 CLI、創意設計與視覺）。
- **完整導覽連結**：一鍵直達 20 大工具專屬手冊，並具備優雅的暗黑毛玻璃（Dark Tech Glassmorphism）現代科技美學。

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

### 11. GitHub CLI (`github-cli.html`) · 自動化第一棒
- **開發者版本控制神器**：`gh` 官方 CLI 工具。
- **核心能力**：規格化自動發起 Pull Request、指派分類 Issue、即時監看 GitHub Actions CI/CD 工作流日誌、跨分支發行版打包（GitHub Release）與 GraphQL API 深度查詢。
- **10 大跨角色實戰範例**：涵蓋開源維護者、DevOps 工程師、後端核心團隊、前端主管、Release Manager、安全合規員等。

### 12. Figma (`figma.html`) · 創意設計第二棒
- **設計與前端工程橋樑**：`figma` 官方外掛與 Code Connect。
- **核心能力**：直接解析 Figma 圖層節點樹 (Node Tree)、擷取色彩字級與間距 Design Tokens、生成 React/Tailwind 元件代碼、批次匯出乾淨向量 SVG 圖標與設計規範稽核。
- **10 大跨角色實戰範例**：涵蓋 UI/UX 設計主管、前端系統架構師、設計工程師 (Design Engineer)、無障礙驗證專員、全端工程師等。

### 13. Notion (`notion.html`) · 協作知識庫第三棒
- **模組化知識庫與看板中樞**：Notion API & 官方生態 MCP。
- **核心能力**：結構化 Database 屬性過濾與關聯查詢、跨專案 Sprint 看板連動、富文本區塊 (Blocks) 智慧排版、會議逐字稿轉結構化行動清單。
- **10 大跨角色實戰範例**：涵蓋敏捷 Scrum Master、技術文件架構師、營運長特助、產品負責人 (PO)、人資入職負責人等。

### 14. n8n 工作流自動化 (`n8n.html`) · 自動化串接第四棒
- **開源自託管工作流引擎**：`n8n-skills` MCP。
- **核心能力**：多節點自動化工作流 JSON 分析與生成、Webhook 雙向即時觸發器、跨系統節點排錯與失敗補償機制、無代碼串接 CRM、Slack/Discord 與資料庫。
- **10 大跨角色實戰範例**：涵蓋自動化架構師、電商營運主管、社群小編自動發文、客服維運工程師、財務報表自動化專家等。

### 15. Supabase (`supabase.html`) · 雲端後端第五棒
- **開源 Firebase 首選替代**：`supabase` 官方外掛與 Postgres MCP。
- **核心能力**：PostgreSQL 表結構 DDL 與高階索引自動生成、精密 Row Level Security (RLS) 權限防禦政策、TypeScript 類型定義自動產生與 Edge Functions 邊緣運算邏輯。
- **10 大跨角色實戰範例**：涵蓋後端資料庫架構師、SaaS 創辦人、資安長、全端 TypeScript 開發者、Mobile 後端工程師等。

### 16. Cloudflare (`cloudflare.html`) · 雲端邊緣第六棒
- **全球邊緣無伺服器與防護中樞**：`antigravity-plugins-partners/plugin/cloudflare`。
- **核心能力**：Workers 邊緣地理路由與反向代理、D1 分散式 SQLite 遷移、零出口頻寬費 R2 物件儲存、Workers AI 邊緣模型推論與 WAF 防火牆自定義防禦規則。
- **10 大跨角色實戰範例**：涵蓋全端架構師、資安 SRE、資料工程師、雲端成本優化師、跨國電商工程師、AI 應用工程師等。

### 17. Stripe (`stripe.html`) · 商業金流第七棒
- **全球商業金流與 SaaS 變現中樞**：`antigravity-plugins-partners/plugin/stripe`。
- **核心能力**：一鍵生成免代碼 Payment Links、SaaS 階梯週期訂閱 (Billing)、Radar 智慧防盜刷評分、爭議款 (Disputes) 自動反擊舉證與 B2B 電子商業發票。
- **10 大跨角色實戰範例**：涵蓋 SaaS 創辦人、電商財務、全端結帳工程師、獨立開發者 (Indie Hacker)、客戶成功主管、資安風控官等。

### 18. Linear (`linear.html`) · 敏捷專案第八棒
- **極速現代軟體工程專案管理標竿**：`antigravity-plugins-partners/plugin/linear`。
- **核心能力**：自然語言需求拆解為 User Story、Sprint Cycles 節奏負載平衡與速率 (Velocity) 預測、Roadmap 產品藍圖進度追蹤與 Git 分支/PR 雙向自動狀態推進。
- **10 大跨角色實戰範例**：涵蓋技術產品負責人 (PO)、敏捷工程主管 (EM)、QA 組長、Release Manager、技術長 (CTO)、Scrum Master 等。

### 19. Atlassian TWG CLI (`atlassian.html`) · 企業脈絡第九棒
- **跨巨型企業工作脈絡全景圖譜**：`antigravity-plugins-partners/plugin/atlassian-twg-cli`。
- **核心能力**：Jira JQL 精密深度檢索、Confluence 知識庫檢索與架構決策 (ADR) 生成、Bitbucket PR 程式審查稽核與 Teamwork Graph 全景實體脈絡整合。
- **10 大跨角色實戰範例**：涵蓋企業架構師、Jira 專案管理員、跨團隊 PM、DevOps 專家、資安稽核員、研發副總 (VP of Eng) 等。

### 20. invideo AI 影音創作 (`invideo.html`) · 影音創作第十棒
- **AI 原生多軌影音編輯與短影音生成**：`antigravity-plugins-partners/plugin/invideo`。
- **核心能力**：自然語言一鍵生成分鏡劇本 (Prompt-to-Video)、神經網路擬真人聲配音、動態逐字卡 (Karaoke Captions)、真實多軌時間軸微調與 16:9 / 9:16 全通路重構。
- **10 大跨角色實戰範例**：涵蓋 YouTube 創作者、電商行銷企劃、企業培訓師、房產經紀人、SaaS 產品經理、社群自媒體經營者等。

### 21. Blender 3D (`blender.html`) · 本機軟體創作第十一棒
- **本機桌面軟體橋接標竿**：`mcp-for-blender` 原生雙層橋接架構 (MCP Server + WebSocket + Blender Add-on)。
- **核心能力**：自然語言程序化 3D 建模 (`bpy`/`bmesh`)、PBR 節點材質 (Principled BSDF) 自動架構、三點棚燈與 HDRI 環境佈光、多模態視覺閉環審查 (`get_viewport_screenshot`) 自我修正、Cycles/Eevee 高動態渲染輸出。
- **使用者基本條件**：完整規範硬體配備 (8GB+ RAM / 獨立顯卡推薦)、軟體相容性 (Blender 3.6 LTS ~ 4.x)、具備 Vision 視覺理解之 AI 語言模型 (Claude 3.5 Sonnet / Gemini 2.0 / GPT-4o)、零程式門檻自然語言驅動，以及本機通訊埠 9876 安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋 3D 概念藝術家、電商產品視覺設計師、獨立遊戲開發者 (Indie Dev)、室內設計與建築表現師、動態圖像設計師 (Motion Designer)、科普教材教師、VFX 電影特效技術總監、3D 列印創客、珠寶配件設計師、科學數據視覺化研究員等。

---

## 📁 檔案結構

```tree
antigravity-tools-guide/
├── index.html                   # 導覽首頁：模組化字卡網格系統 (收錄 20 大旗艦專題)
├── chrome-devtools.html         # Chrome DevTools MCP 詳細教學指南
├── google-drive-docs.html       # Google Drive & Docs 完整使用指南
├── google-sheets.html           # Google Sheets 試算表與數據分析指南
├── gmail-calendar.html          # Gmail & Google Calendar 個人 AI 秘書指南
├── google-slides.html           # Google Slides 視覺簡報與 SOIL 架構指南
├── google-notebooklm.html       # Google NotebookLM 深度研究與播客生成指南
├── firebase.html                # Firebase 全端後端與 Security Rules 指南
├── google-cloud-gemini.html     # Google Cloud & Gemini Developer 旗艦指南
├── canva.html                   # Canva AI 視覺設計與行銷自動化指南
├── github-cli.html              # GitHub CLI 開發者版本控制與 CI/CD 指南
├── figma.html                   # Figma 設計系統與 Design-to-Code 指南
├── notion.html                  # Notion 模組化資料庫與團隊知識庫指南
├── n8n.html                     # n8n 開源工作流編排與 Webhook 自動化指南
├── supabase.html                # Supabase PostgreSQL、RLS 與 Edge Functions 指南
├── cloudflare.html              # Cloudflare 邊緣運算、D1/R2 與 WAF 指南
├── stripe.html                  # Stripe 全球金流、SaaS 訂閱與財務指南
├── linear.html                  # Linear 極速敏捷專案管理與 Cycles 指南
├── atlassian.html               # Atlassian TWG CLI Jira、Confluence 企業脈絡指南
├── invideo.html                 # invideo AI 影音創作與時間軸短影音指南
├── blender.html                 # Blender 3D 程序建模、PBR 材質與視口截圖指南
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
