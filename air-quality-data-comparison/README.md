# air-quality-data-comparison site data

Per-site Parquet and metrics JSON for the
[air-quality-data-comparison](https://github.com/ashiklom/simon-code-research/tree/main/air-quality-data-comparison)
website (https://ashiklom.github.io/simon-code-research/air-quality-data-comparison/).

- Produced by `mise run sitedata` in that experiment (`site/public/data`), copied here by
  `scripts/publish_site_data.sh`.
- Read by the browser (`site/src/main.js`) from `raw.githubusercontent.com` at the commit pinned in
  the experiment's `site/.env.production` (`VITE_DATA_BASE`).
- Layout: `data/{sites,products,summary,scales}.json`; `data/site/<id>/{daily,monthly}.parquet`,
  `hourly/2023.parquet`, `metrics.json`.
