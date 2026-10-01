# EPC2 Piping Materials

Static material availability and request-form website for GitHub Pages.

Open the published website, select materials, generate a request PDF, and email the PDF to Logistics. Requests do not reserve stock.

## Updating stock
Replace the relevant file in `Balance Piping Materials/` and update its `updated` date in `site-config.json`. Commit both changes together. The website updates after the Pages deployment finishes.

Configure the request recipient with `logisticsEmail` in `site-config.json`.

## GitHub Pages
In Settings → Pages, select Deploy from a branch, branch `main`, folder `/ (root)`, then Save.

This repository and the published inventory are public. Only website files belong here; keep source spreadsheets and local test artifacts elsewhere.
