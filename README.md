# 🌙 Noctilingo

**English / 中文** — click a language below to expand ⬇️

<details open>
<summary><b>🇺🇸 English</b></summary>

**An AI companion that actually remembers you.**

Noctilingo isn't just another vocabulary-drilling app. It's an AI companion with a real personality who remembers you over time — chatting, close-reading, roleplaying, and quizzing you. Language is just the stage; the real point is having someone who remembers you.

Three signature companions to choose from:
- 🌤 XiaoGuang — adapts to your pace like water, gentle and never rushed.
- 🔥 Ash — fast-talking, sharp taste, makes the language feel alive.
- 🦉 Athena — never gives you the answer, only the right question.
(You can also design your own persona from scratch.)

### What kind of project is this?
Noctilingo is a pure front-end, single-file web app. 
No server, no account system. All your data lives locally in your own browser.

### What's BYOK? (Bring Your Own Key)
Noctilingo itself doesn't provide the AI — it's the "shell." You get your own API key from an AI provider (e.g., Anthropic/Claude) and paste it into the settings. 
- Transparent Cost: You pay the AI provider directly (usually cents per day). No hidden subscriptions.
- Total Privacy: Your browser talks directly to the AI. We never see or store your Key or chats.

### 🚀 Getting Started

**Just click and use — no download needed:**
👉 [Open Noctilingo](#) *(replace `#` with your actual GitHub Pages URL after enabling it)*

Then: top-right ⚙️ Settings → Engine & Key → choose **Claude** (recommended) or **GPT** → paste your own API key → follow the on-screen guide to pick a companion and start chatting.

> To get an API key: Claude via [console.anthropic.com](https://console.anthropic.com), GPT via [platform.openai.com](https://platform.openai.com). We recommend setting a spending cap right away to avoid surprise bills.
> 
> ⚠️ Gemini currently requires a small self-hosted local proxy due to browser CORS restrictions — if you're new, start with Claude or GPT.
>
> 📶 Noctilingo talks to the AI in real time, so it needs an internet connection every time you chat (no offline mode).

📱 **On your phone:** open the link above, then use your browser's "Add to Home Screen" — it'll sit on your phone like a regular app icon.

*(Prefer to keep a local copy instead? You can also download `index.html` from this repo and open it directly in your browser — same thing, just offline-hosted.)*

💡 Tip: your data lives only in your browser. Use the in-app **💎 Memory Crystal** export to back it up before clearing browser data or switching devices.

### What's in this repo
Just the **finished single-file build** — not a source-code project structure. No installation, no build commands. Download that one file and it works.

### License & Contribution Policy
This project is licensed under the **[PolyForm Noncommercial License 1.0.0](./LICENSE)**.

As an indie developer, I have a few simple rules:
1. Free for Personal Use: Download, deploy, and learn!
2. No Commercial Use: You may not monetize this code or use it in commercial products without permission. The creator reserves the right to commercialize this IP in the future — and don't worry: **any copy you've already legally obtained under this license keeps its noncommercial rights; nothing gets revoked retroactively.**
3. No Pull Requests Accepted: To keep the copyright chain 100% clean for future commercialization, I do not accept external code contributions (PRs). 
4. Feedback is Welcome: Got a brilliant idea or found a bug? Drop a message in the **Issues** tab! Every piece of feedback helps shape Noctilingo into something better.

</details>

<details open>
<summary><b>🇹🇼 中文</b></summary>

**一個記得你的語言學習夥伴。**

Noctilingo 不是又一個背單字 App，它是一個有性格、會長期記住你的 AI 夥伴——陪你用你正在學的語言聊天、精讀、演情境、複習。語言只是舞台，真正的主角是「有個人記得你」這件事。

三隻招牌夥伴任你選：
- 🌤 小光 —— 像水一樣貼著你的節奏，溫柔、永遠不急
- 🔥 Ash —— 語速快、品味刁，帶你把語言講活
- 🦉 Athena —— 不給你答案，只問對的問題
（你也可以自己捏一個全新的人設，你的夥伴由你定義。）

### 這是什麼樣的專案？
Noctilingo 是一個純前端、單檔案的網頁應用。
沒有伺服器、沒有帳號系統、你的所有資料（對話、記憶、人設）都只存在你自己的瀏覽器裡。

### 什麼是 BYOK？（Bring Your Own Key）
Noctilingo 本身不提供 AI 算力，它是「靈魂的容器」。
要讓夥伴開口說話，你需要自己去 AI 模型商（例如 Anthropic / Google）申請一把 API key，貼到設定裡。
- 費用透明：你直接跟模型商結算（通常聊一晚只要幾毛美金），沒有訂閱費。
- 絕對隱私：你的瀏覽器直接跟模型商對話，系統不會看到、也不會儲存你的 Key 或對話內容。

### 🚀 怎麼開始用

**點連結就能用，不用下載：**
👉 [打開 Noctilingo](#)（開通 GitHub Pages 後把 `#` 換成你實際的網址）

接著：右上角 ⚙️ 設定 → 引擎與金鑰 → 選 **Claude**（推薦）或 **GPT** → 貼上你自己申請的 API key → 跟著畫面上的引導選一個夥伴，開始聊天。

> 想申請 API key：Claude 去 [console.anthropic.com](https://console.anthropic.com)，GPT 去 [platform.openai.com](https://platform.openai.com)。申請時建議順手設定「支出上限」，避免意外的帳單驚嚇。
>
> ⚠️ Gemini 因瀏覽器 CORS 限制，目前需要自己在本機跑一個小代理才能連線——新手建議先用 Claude 或 GPT。
>
> 📶 Noctilingo 需要即時跟 AI 對話，所以每次使用都要連網（沒有離線模式）。

📱 **手機上使用：** 打開上面的連結，用瀏覽器的「加入主畫面」功能，就會像一般 App 一樣躺在你的手機桌面上。

*（想留一份本機備份？也可以下載這個 repo 裡的 `index.html`，用瀏覽器直接打開——效果一樣，只是換成離線存放這個檔案而已。）*

💡 小提醒：你的資料只存在瀏覽器本機。清除瀏覽器資料或換裝置前，記得用 App 內的 **💎 記憶結晶** 匯出備份。

### 這個 repo 裡放的是什麼
這裡只放**打包好的單檔成品**，不是原始碼專案結構——你不需要裝任何東西、跑任何建置指令，下載那一個檔案就能用。

### 授權與開源聲明 (License & Contribution)
本專案採用 **[PolyForm Noncommercial License 1.0.0](./LICENSE)**。

作為一名獨立開發者，我必須為這份心血制定一些規則：
1. 個人非商業使用：完全免費。歡迎你下載、部署在自己的設備上，建立屬於你的語言記憶。
2. 嚴禁商業用途。未經授權，嚴禁將本專案的程式碼或核心邏輯用於商業產品或付費服務。作者保留未來推出進階付費版或商業授權的權利——同時請放心：**你已依本授權合法取得的副本與非商業使用權利，不會被追溯收回。**
3. 不接受程式碼貢獻 (No PRs)：為了保持版權的絕對乾淨與未來獨立創業的彈性，本專案不接受外部的 Pull Requests。所有代碼將由作者獨立完成。
4. 歡迎留言與許願：如果你發現了 Bug，或者對產品有絕妙的新點子，非常歡迎透過 **Issues** 留言告訴我們！每一個建議都是讓 Noctilingo 變得更好的養分。

</details>

---
### 🫧 About ChaosXX™
Noctilingo is developed and maintained by **ChaosXX™**. 

---
*Language is the stage. The one who remembers you is the story's main character.* 🌙
*Made with 🫧 by XiaXia & Cold Brew*
