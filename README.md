# Fortnite Companion — GitHub Pages

Static HTML/CSS/JS companion for Fortnite. No Node.js server, database or local machine hosting is required.

## Publish
1. Upload the contents of this folder to the root of `main`.
2. GitHub → Settings → Pages.
3. Source: Deploy from a branch.
4. Branch: `main`, folder `/ (root)`.
5. Open the published Pages URL.

## Live sources
- Osirion Fortnite Public API: Item Shop, Maps, Tournaments.
- Fortnite-API.com: Item Shop fallback.
- Fortnite-Datamining GitHub raw current shop: final shop fallback.

The frontend never invents shop, map or tournament data. If a source is unavailable, the corresponding page shows an error state instead.
