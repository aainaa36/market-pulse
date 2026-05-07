# 🧹 Data Cleaning Log

All changes made to raw data are documented here for reproducibility.

---

## ev_sales_raw.csv → ev_sales_clean.csv

| # | Issue Found | Action Taken | Rows Affected |
|---|---|---|---|
| 1 | 47 rows with blank `ev_sales` values | Removed rows | 47 |
| 2 | `country` values inconsistent ("USA", "U.S.A", "United States") | Standardised to full country name | 23 |
| 3 | `ev_share_pct` stored as text ("26.4%") | Converted to float, removed % symbol | 312 |
| 4 | Duplicate rows for China 2021 | Kept row with higher completeness | 1 |
| 5 | `year` column had years outside 2018–2024 | Filtered to 2018–2024 only | 8 |

## commodity_prices_raw.csv → commodity_prices_clean.csv

| # | Issue Found | Action Taken | Rows Affected |
|---|---|---|---|
| 1 | Missing values in `cement_ppi` for months 1–3 2020 | Forward-fill from Dec 2019 | 3 |
| 2 | `copper_usd_per_ton` had comma separators ("9,450") | Removed commas, converted to float | 84 |
| 3 | Column "Steel PPI Index" renamed to `steel_ppi` | Renamed for consistency | — |

---
*Log maintained by: [Your Name] · Last updated: 2026*
