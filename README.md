# Antigravity 擴充工具庫指南 (Antigravity Tools Hub)

> 一站式探索與掌握 AI Agent 必備外掛、MCP 協議與自動化工具知識庫。

🌐 **線上即時預覽 (GitHub Pages)**: [https://clive520.github.io/antigravity-tools-guide/](https://clive520.github.io/antigravity-tools-guide/)

---

## 📖 專案簡介

本專案收錄並整理 Antigravity 2.0 擴充套件市場（Marketplace）中官方與合作夥伴提供的關鍵工具使用指南，旨在幫助開發者、教育工作者、設計師、數據分析師與各領域專業人士充分發揮 AI Agent 的自動化、雲端協作與視覺生產力。

目前已全面完成收錄 **Chrome DevTools**、**Google 家族（Google Family）全系列核心服務**、**Canva AI 視覺設計旗艦生態**、**開發者自動化前五棒（GitHub CLI、Figma、Notion、n8n、Supabase）**、**擴充第 6～10 棒（Cloudflare、Stripe、Linear、Atlassian TWG、invideo）**，以及**本機桌面軟體旗艦八棒（Blender 3D、OBS Studio、FreeCAD、Krita、Unity Editor、Inkscape、REAPER DAW、Adobe Photoshop）**，共計 27 大旗艦工具專題頁面與 270 組以上跨角色實戰 Prompt。

---

## 🌟 收錄專題與指南矩陣

### 1. 核心首頁與導航 (`index.html`)
- **模組化高擴充性字卡網格（Card Grid）**：支援即時關鍵字模糊搜尋、多類別標籤過濾（全部、辦公協作與知識庫、後端與除錯、自動化與 CLI、創意設計與視覺）。
- **完整導覽連結**：一鍵直達 27 大工具專屬手冊，並具備優雅的暗黑毛玻璃（Dark Tech Glassmorphism）現代科技美學。

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

### 22. OBS Studio (`obs.html`) · 本機軟體創作第十二棒
- **本機影音錄播與導播中樞**：`obs-websocket 5.x` 原生雙層協議橋接 (`@royshil/obs-mcp` / `obs-mcp`)。
- **核心能力**：自然語言多鏡頭與畫中畫 (PiP) 自動排版、平滑轉場動態切換、多音軌平衡與側鏈壓低 (Audio Ducking)、自動化本機錄影與 RTMP 推流、即時畫布快照審查 (`obs_media_take_screenshot`) 視覺自檢閉環。
- **使用者基本條件**：OBS Studio 28.0+（內建 WebSocket，100% 免額外裝外掛）、8GB+ RAM / 硬體編碼加速、具備 Vision 視覺理解能力之 AI 語言模型、零程式碼門檻、本機環回通訊埠 4455 安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋線上教學教師、遊戲實況主、SaaS 產品經理、跨國線上座談主持、影音播客 (Video Podcast)、虛擬 VTuber 實況、無障礙導讀員、軟體 QA 測試員、電商直播帶貨、AI 智慧導播總監等。

### 23. FreeCAD (`freecad.html`) · 本機軟體創作第十三棒
- **開源參數化 3D CAD/CAM 建模神器**：`freecad-mcp` 本機 RPC / Python API 服務橋接。
- **核心能力**：自然語言草圖約束 (`Sketcher`)、PartDesign 實體特徵造型（拉伸/倒角/布林運算）、組裝關係約束、STEP/STL 工程檔解析與 3D 列印 G-code 切片參數核查。
- **使用者基本條件**：FreeCAD 0.21+ / 1.0+（內建 Python 3 API）、8GB+ RAM / 支援 OpenGL 3.0+ 顯卡、具備空間拓撲推理之 AI 語言模型、零 Python 腳本門檻、本機環回通訊埠 9000 安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋機械工程師、3D 列印創客、工業產品設計師、機器人結構研發、建築與模組化構件師、工裝夾具技工、科普 STEM 教師、硬體新創原型師、逆向工程審計師、精密公差驗證工程師等。

### 24. Krita (`krita.html`) · 本機軟體創作第十四棒
- **開源專業數位繪畫與插畫中樞**：`krita-mcp` FastMCP + Krita 本機 Python Plugin (PyQt5)。
- **核心能力**：自然語言畫布圖層管理（Blending Modes / 剪裁遮罩）、筆刷引擎動態切換、色環配色調色盤調配、視口畫布即時 Base64 快照視覺自檢與多圖層 PSD/KRA 匯出。
- **使用者基本條件**：Krita 5.0+（內建 Python 腳本工具）、8GB+ RAM / 繪圖板支援、具備 Vision 視覺理解能力之 AI 語言模型、零腳本門檻、本機通訊埠 8080 安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋概念插畫家、動漫分鏡漫畫家、遊戲 2D 骨骼貼圖師、UI/UX 圖標繪製師、童書繪本創作者、美術概念設定總監、水彩擬真手繪畫家、社群縮圖視覺企劃、數位繪畫培訓教師、復古像素藝術家等。

### 25. Unity Editor (`unity.html`) · 本機軟體創作第十五棒
- **全球頂尖跨平台遊戲引擎與即時 3D 創作**：`unity-mcp` C# Editor Bridge WebSocket 連線。
- **核心能力**：自然語言階層樹 (Hierarchy) 與場景物件巡檢、Inspector 元件參數動態微調、Prefabs 預製物實例化與關聯擺放、Console 報錯堆疊反查與場景相機視角截圖自檢。
- **使用者基本條件**：Unity 2021.3 LTS / 2022.3 LTS / Unity 6、16GB+ RAM / 獨立顯卡加速、具備遊戲架構推理之 AI 語言模型、零 C# 繁瑣反射門檻、本機環回通訊埠 8080 安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋獨立遊戲製作人、關卡設計師 (Level Designer)、遊戲技術美術 (TA)、遊戲客戶端主程、Unity QA 自動化工程師、XR/VR 虛擬實境開發者、遊戲音效與音效觸發工程師、手機遊戲效能優化師、遊戲教學講師、UI 元件佈局工程師等。

### 26. Inkscape (`inkscape.html`) · 本機軟體創作第十六棒
- **開源專業向量向量插畫與標準 SVG 設計神器**：`inkscape-mcp` FastMCP + Inkscape Actions CLI。
- **核心能力**：自然語言標準 W3C SVG 向量繪製、貝茲曲線節點與平滑優化、布林運算（聯集/交集/差集/打散）、幾何對齊與網格分佈、多解析度 PNG/PDF/WebP 批次算繪匯出。
- **使用者基本條件**：Inkscape 1.2+ / 1.3+（支援完整 Actions 命令行介面）、4GB+ RAM、具備向量幾何空間推理之 AI 語言模型、零 CLI 指令門檻、本機無連網純檔案隔離沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋向量插畫家、UI 圖標設計師 (Icon Designer)、雷射雕刻與 CNC 創客、品牌識別 (Logo) 設計師、技術文件架構圖繪製員、字型與字體設計師 (Typography)、向量地圖繪製員、包裝刀模與紙模工程師、服裝與刺繡打版師、向量視覺藝術教育者等。

### 27. REAPER DAW (`reaper.html`) · 本機軟體創作第十七棒
- **極致輕量與極限擴充之專業數位音訊工作站**：`reaper-mcp` ReaScript / Python API (`reapy`)。
- **核心能力**：多軌音訊排列與標籤管理、VST/AU 效果器鏈參數自動化調整、自然語言音訊波形切分與對齊 (Ripple Editing)、LUFS 響度正規化與即時音軌快照審查。
- **使用者基本條件**：REAPER 6.x / 7.x（內建 ReaScript 擴充環境）、4GB+ RAM / ASIO 低延遲音效卡、具備專業音訊聲學理解之 AI 語言模型、零 ReaScript 寫碼門檻、本機通訊安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋 Podcast 剪輯後製師、音樂製作人 (Producer)、遊戲擬音與音效設計師 (Foley/Sound Designer)、配音錄音室工程師、影視配樂混音師、Mastering 母帶後期工程師、廣播電台成音工程師、有聲書製作總監、無障礙語音處理專員、成音工程教學講師等。

### 28. Adobe Photoshop (`photoshop.html`) · 本機軟體創作第十八棒
- **全球商業數位影像處理與視覺設計黃金標竿**：`photoshop-mcp` ExtendScript / UXP / WebSocket Bridge。
- **核心能力**：多圖層樹狀階層管理、非破壞性調整圖層與智慧型濾鏡套用、精密選區與羽化遮罩建立、畫布畫板 (Artboards) 全尺寸動態重構、Web 格式批次裁切與自動化命名匯出。
- **使用者基本條件**：Adobe Photoshop CC 2021+（支援 UXP / Generator / 腳本監聽器）、16GB+ RAM / GPU 加速支援、具備多模態視覺色彩審美之 AI 語言模型、零 ExtendScript 代碼門檻、本機通訊埠安全沙盒驗證。
- **10 大跨角色實戰範例**：涵蓋商業修圖師 (Retoucher)、電商主圖與廣告設計師、電影海報視覺總監、社群視覺小編、數位霧面繪畫師 (Matte Painter)、攝影師後製助理、UI 設計資產切圖師、包裝印刷色彩管理師、視覺行銷藝術指導、影像合成教學名師等。

---

## 📁 檔案結構

```tree
antigravity-tools-guide/
├── index.html                   # 導覽首頁：模組化字卡網格系統 (收錄 27 大旗艦專題)
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
├── obs.html                     # OBS Studio 直播錄影與 AI 智慧導播指南
├── freecad.html                 # FreeCAD 參數化 3D CAD/CAM 工程建模指南
├── krita.html                   # Krita 數位繪圖、概念插畫與分鏡草稿指南
├── unity.html                   # Unity Editor 遊戲引擎開發與場景物件指南
├── inkscape.html                # Inkscape 向量插畫、UI 圖標與 SVG 繪圖指南
├── reaper.html                  # REAPER DAW 數位音訊工作站與混音剪輯指南
├── photoshop.html               # Adobe Photoshop 影像處理與圖層自動化指南
├── plans/                       # 桌面軟體 MCP 循序開發計畫書庫
│   ├── 01_obs_studio_mcp_plan.md# OBS Studio MCP 完整開發計畫書
│   ├── 02_freecad_mcp_plan.md   # FreeCAD MCP 完整開發計畫書
│   ├── 03_krita_mcp_plan.md     # Krita MCP 完整開發計畫書
│   ├── 04_unity_mcp_plan.md     # Unity Editor MCP 完整開發計畫書
│   ├── 05_inkscape_mcp_plan.md  # Inkscape MCP 完整開發計畫書
│   ├── 06_reaper_mcp_plan.md    # REAPER DAW MCP 完整開發計畫書
│   └── 07_photoshop_mcp_plan.md # Adobe Photoshop MCP 完整開發計畫書
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
