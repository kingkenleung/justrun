# JustRun

**🔗 https://kingkenleung.github.io/justrun/**

用 AI（Gemini / ChatGPT）生成了 HTML App，但不知道怎麼執行或分享？JustRun 幫你搞定。  
Got HTML from an AI but have no idea how to run it? JustRun fixes that.

---

## Tools · 工具

### 1. HTML Code Downloader · HTML 代碼下載器
Paste your AI-generated HTML → download it as a proper `myapp.html` file.  
Bypasses the Windows hidden file extension problem (no more `myapp.html.txt`).

### 2. Live App Sharing · 即時分享工具
Paste your code → get a shareable link + QR Code instantly.  
Anyone can scan to run your app in their browser. No server, no account.  
Powered by **WebRTC P2P** — your code is never stored on any server.

---

## How It Works · 使用方式

**Run on your own computer:**
1. Get HTML code from Gemini / ChatGPT
2. Go to the Downloader → paste → download `myapp.html`
3. Double-click the file to open in browser

**Share with others:**
1. Get HTML code from Gemini / ChatGPT
2. Go to the Sharing tool → paste → click "Start Hosting"
3. Share the generated link or QR Code — keep the tab open

---

## Notes · 注意

- The sharing tool requires your browser tab to stay open; the link expires when you close it.
- If connection times out, ask the other person to use mobile data (4G/5G) to bypass school/corporate firewalls.
- Zero dependencies to install. Everything runs in the browser.

---

## Tech Stack

- Vanilla HTML / CSS / JS
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [PeerJS](https://peerjs.com/) for WebRTC P2P
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) for QR generation
