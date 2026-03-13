# 🔄 URL Auto-Refresher

A dead-simple tool that silently auto-refreshes up to 15 URLs on a configurable timer. Zero dependencies, pure HTML/CSS/JS.

## What it does

- Add up to **15 URLs** and each one gets reloaded in a hidden iframe on a loop
- **Per-URL countdown** showing seconds until next refresh + timestamp of last hit
- **Adjustable interval** — default 15s, configurable from 1–300s
- **Pause / Resume** all refreshes with one click
- Green flash on each row when it fires

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/url-refresher)

Or manually:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

That's it. No build step, no framework — Vercel serves the static `public/` directory.

## Run locally

Just open the file:

```bash
open public/index.html
```

Or use any static server:

```bash
npx serve public
```

## Project structure

```
url-refresher/
├── public/
│   └── index.html    # The entire app — single file
├── vercel.json       # Vercel routing config
├── .gitignore
├── LICENSE
└── README.md
```

## Caveat

Many sites block iframe embedding via `X-Frame-Options` or CSP headers, so the background fetch won't visually load for every URL. The request is still made though, which is useful for keep-alive pings, dashboards, or sites you control.

## License

MIT
