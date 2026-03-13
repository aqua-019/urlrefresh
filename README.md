# ⚡ Matty-San, tik-tok god

Hyper URL auto-refresher with vibes. Silently refreshes up to **100 URLs** in the background, each on its own configurable timer from **0.1s to 15s**.

Now with 15 kawaii anime girls, chaotic SJB83 typography, and a "Daddy needs VIEWS" popup.

## Features

- **100 URL slots** — add individually or bulk import
- **Per-URL refresh rate** — logarithmic slider from 0.1s to 15s per slot
- **Single rAF loop** — one `requestAnimationFrame` tick drives everything
- **Bulk import** — paste a list of URLs, one per line
- **"Daddy needs VIEWS"** popup on every add
- **SJB83** scattered across the page in random grey/white fonts, sizes, and orientations
- **15 kawaii anime girls** (10 full + 5 chibi) procedurally generated with randomized hair, outfits, eyes, expressions, and accessories
- **Zero dependencies** — single HTML file, no build step

## Deploy

### Vercel (recommended)

```bash
npm i -g vercel
vercel
```

### Local

```bash
open public/index.html
```

## Structure

```
├── public/
│   └── index.html
├── vercel.json
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚖️📜 Legal Disclaimer & Terms of Use 🔒

🌐 This tool is a **general-purpose URL refresher** designed for **development testing**, QA workflows, endpoint monitoring, and personal browsing convenience. It functions by periodically loading user-specified URLs in the background — the functional equivalent of a user manually pressing the refresh button in their browser at their own preferred interval. 🔄

✅ This utility performs **standard HTTP requests** identical to those made by any modern web browser. No headers are spoofed, no authentication is bypassed, no rate-limiting mechanisms are circumvented, and no terms of service are inherently violated by the act of requesting a publicly accessible URL. Every request originates from the user's own browser and IP address. 🖥️

⚠️ **User Responsibility:** The end user assumes full responsibility for how this tool is used. It is the user's obligation to ensure that their use of this tool complies with all applicable laws, regulations, and terms of service of any website or platform they choose to interact with. The developers of this tool do not endorse, encourage, or condone the use of this software for any purpose that violates the terms of service of any third-party platform. 📋

🔒 This tool does not collect, store, transmit, or process any user data. All URLs and configuration remain local to the user's browser session. No analytics, no cookies, no tracking. 🛡️

🧪 **Intended Use Cases:** Frontend development hot-reload testing, API endpoint health monitoring, dashboard auto-refresh, staging environment QA, load simulation on your own infrastructure, and visiting webpages at your own preferred rate. 🔧

📝 By using this tool, you acknowledge that you have read and understood this disclaimer and agree to use the software responsibly and in compliance with all applicable laws. 🤝

---

© 2026 Matty-San · SJB83 · MIT License · Built for development & testing purposes only ⚡

## License

MIT
