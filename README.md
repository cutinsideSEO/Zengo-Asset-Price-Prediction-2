# Solana Price Prediction — single-file build

**One self-contained file: `index.html`.** Everything (React, all components, CSS, fonts,
logos, the coin image) is embedded inside it. No folders, no relative paths — it cannot break
on upload.

## Deploy to GitHub Pages
1. Put `index.html` in your repo (root).
2. Settings → Pages → Branch `main`, Folder `/ (root)`.
3. Open the Pages URL. Done.

It also works opened directly in a browser (double-click) and on any static host.

## Notes
- **Live data** (Polymarket odds, CoinGecko price, Fear & Greed) still loads from the internet
  and refreshes every 60s; offline it falls back to sample data.
- This is a **review build** — it compiles React in the browser. For the production SEO page,
  use the multi-file source repo and pre-compile the JSX / server-render (see that repo's README).
