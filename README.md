# 交易所高息理財日報

Static GitHub Pages site for daily exchange high-yield / wealth-management news.

- **Repo:** `taihangFu/exchange-earn-daily`
- **Schema:** v1 — `schemaVersion` / `date` / `updatedAt` / `headlines[]` / `whaleNotes[]`
- **Headline required fields:** `title` / `summary` / `whyCare` / `link` / `date` / `source` / `tags` / `regionNote`
- **Unique draft path (do not fork):** `/workspace/exchange-earn-site/data.json`
- Publish from `main` with Pages source **Deploy from a branch → main → / (root)**.

`regionNote` must be rendered under each card (after `whyCare`, before footer). Trim-empty values are hidden; schema still requires the field on every headline.
