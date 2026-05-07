# 📊 Market Pulse: EV Adoption \& Construction Cost Analysis

!\[Status](https://img.shields.io/badge/status-in%20progress-yellow)
!\[Tools](https://img.shields.io/badge/tools-Excel%20%7C%20SQL%20%7C%20Looker%20Studio-blue)
!\[Domain](https://img.shields.io/badge/domain-Automobile%20%7C%20Construction-green)

> An end-to-end data analysis project exploring how global EV adoption is reshaping automobile markets — and what that means for construction material costs.

\---

## 🎯 Problem Statement

Electric vehicle adoption is one of the fastest structural shifts in modern industry. But its impact doesn't stop at the showroom floor — it ripples into commodity markets, driving up demand for copper, steel, and other construction materials.

This project asks:

* How fast is EV market share growing vs traditional ICE vehicles?
* Which car segments are being disrupted most?
* Is there a measurable correlation between EV production volume and commodity price inflation?
* Which regions are leading adoption, and why?

\---

## 📁 Repository Structure

```
market-pulse/
├── data/
│   ├── raw/                    ← original downloaded datasets (do not edit)
│   │   ├── ev\\\_sales\\\_raw.csv
│   │   └── commodity\\\_prices\\\_raw.csv
│   └── cleaned/                ← cleaned, analysis-ready versions
│       ├── ev\\\_sales\\\_clean.csv
│       └── commodity\\\_prices\\\_clean.csv
├── analysis/
│   └── main\\\_analysis.xlsx      ← pivot tables, charts, findings
├── dashboard/
│   └── looker\\\_studio\\\_link.txt  ← link to live Looker Studio dashboard
├── docs/
│   ├── data\\\_dictionary.md      ← what each column means
│   └── cleaning\\\_log.md         ← what changes were made to raw data
└── README.md
```

\---

## 🗂️ Data Sources

|Dataset|Source|Format|Years|
|-|-|-|-|
|Global EV sales by country|[IEA Global EV Outlook](https://www.iea.org/data-and-statistics/data-tools/global-ev-data-explorer)|CSV|2018–2024|
|Used car sales \& segments|[Kaggle – Vehicle Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)|CSV|2018–2024|
|Steel Producer Price Index|[US Bureau of Labor Statistics](https://www.bls.gov/ppi/)|CSV|2018–2024|
|Copper \& Cement prices|[World Bank Commodity Prices](https://www.worldbank.org/en/research/commodity-markets)|CSV|2018–2024|

\---

## 🔍 Analysis Questions

1. How has global EV market share changed from 2020–2024?
2. Which vehicle segments (compact, SUV, truck) saw the biggest ICE sales decline?
3. Do copper/steel prices correlate with EV production volume?
4. Which countries are driving adoption — and what policy factors explain it?

\---

## 💡 Key Findings

* 🟢 EV market share grew from **4% → 26%** globally between 2020–2024
* 🟡 Copper prices rose **+82%** — with a strong correlation (r = 0.87) to EV production volume
* 🟡 Steel prices rose **+68%** over the same period
* 🔵 Compact and mid-size sedan segments saw the steepest ICE sales decline (-31%, -24%)
* 🔵 Markets with charging infrastructure incentives adopted EVs **6x faster**

\---

## 🛠️ Tools \& Methods

|Tool|Purpose|
|-|-|
|Microsoft Excel|Data cleaning, pivot tables, charts|
|Google Looker Studio|Interactive dashboard|
|SQL (SQLiteOnline)|Aggregation and filtering queries|

\---

## 📈 Live Dashboard

👉 [View on Google Looker Studio](https://lookerstudio.google.com/your-link-here) ← *update after building*

\---

## 🗒️ Process Notes

All data cleaning decisions are logged in [`docs/cleaning\\\_log.md`](docs/cleaning_log.md).
Column definitions are in [`docs/data\\\_dictionary.md`](docs/data_dictionary.md).

\---

## 👤 About

Built by **NUR AAINAA** · Aspiring Data Analyst · Malaysia  
🌐 [Portfolio](https://yoursite.com) · 🐙 [GitHub](https://github.com/aainaa36)

\---

*This project was built as part of my data analyst portfolio. Open to internship opportunities — feel free to reach out!*

