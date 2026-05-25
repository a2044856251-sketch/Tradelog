# TradeLog

A single-file crypto trading journal web app. No build step, no server — just open `index.html` in a browser.

Built with vanilla HTML/CSS/JS by a self-taught developer who trades crypto and builds AI tools.

## Features

- **Offline-first** — All data stored locally via IndexedDB (Dexie.js). Nothing leaves your machine.
- **Stats dashboard** — Win rate, P&L, R-multiple, expectancy, and more
- **Charts** — Equity curve, P&L distribution, win/loss calendar heatmap (Chart.js)
- **Screenshot support** — Attach chart screenshots to trades with automatic compression
- **Backup/restore** — Export/import all trades as JSON
- **Custom symbols & patterns** — Editable dropdowns persisted in localStorage
- **Dark UI** — Glassmorphism design, Morandi palette

## Tech Stack

| Layer | Choice |
|-------|--------|
| Database | [Dexie.js](https://dexie.org/) (IndexedDB wrapper) |
| Charts | [Chart.js](https://www.chartjs.org/) |
| UI | Vanilla HTML/CSS/JS, zero dependencies beyond the two CDN scripts |
| Hosting | GitHub Pages (single `index.html`) |

## Why This Exists

I trade crypto and wanted a journal that:
- Works offline with no account or cloud dependency
- Is fast — single HTML file, loads instantly
- I can extend myself without fighting a framework

This is also part of my transition into the Crypto × AI space — demonstrating I can ship working products at the intersection of trading and technology.

## Try It

```
git clone https://github.com/a2044856251-sketch/Tradelog.git
cd tradelog
open index.html
```

Or deploy to GitHub Pages: Settings → Pages → Source: `main` branch, root folder.

## Author

**浅海** — Crypto trader, AI tool builder, self-taught developer.

- Building at the intersection of trading, AI agents, and Web3
- Currently seeking roles in Crypto × AI companies
