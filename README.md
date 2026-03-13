# ⚡ Matty-San, tik-tok god

Hyper URL auto-refresher with vibes. Silently refreshes up to **100 URLs** in the background, each on its own configurable timer from **0.1s to 15s**.

Now with anime girls and chaos.

## Features

- **100 URL slots** — add individually or bulk import
- **Per-URL refresh rate** — logarithmic slider from 0.1s to 15s per slot
- **Single rAF loop** — one `requestAnimationFrame` tick drives everything
- **Bulk import** — paste a list of URLs, one per line
- **"Daddy needs VIEWS"** popup on every add
- **SJB83** scattered across the page in random fonts, sizes, and orientations
- **Kawaii anime girls** haunting the corners
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

## License

MIT
