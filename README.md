# Ecommerce Discount Strategy Analysis
Data analysis project investigating whether discounts help or hurt an e-commerce company. Covers discount depth, seasonal sales patterns (Black Friday, Christmas), product categorisation, and price distribution. Presented to a simulated company board.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![VS Code](https://img.shields.io/badge/VS%20Code-IDE-blue)

## Context
This project was completed as part of a data analytics training programme, using internal sales data from a fictional e-commerce company facing a real strategic question: are discounts helping or hurting the business?

## Overview
Eniac, a growing e-commerce company, is caught in an internal debate. The Marketing team believes discounts drive customer acquisition and long-term growth. The Board worries that aggressive pricing is quietly eroding revenue. Both sides have a point. Neither has the data to prove it.

This project analyses Eniac's order and product data to answer two critical questions:

1. **Is discounting financially beneficial for Eniac?**
2. **Are discounts being used tactically, or have they become structural?**

## Dataset
Four interconnected internal CSV files covering Eniac's operations.

| Table | Raw rows | After cleaning|
|---|---|---|
| Orders | 226,614 | 40,985 |
| Orderlines | 293,983 | 53,231 |
| Products | 10,580 | 9,992 |
| Brands | 187 | unchanged |

Cleaning steps included duplicate removal, handling missing values, and filtering out malformed entries. The dataset required substantial work before analysis could begin.

## Project Files
| File | Description |
|---|---|
| 📊 [Data (CSVs)](https://drive.google.com/drive/folders/1kr97tIuWYcog47rGFR3R-xCy2yl-qg3P?usp=drive_link) | Raw, cleaned, and quality-controlled tables |
| 📉 [Plots](https://drive.google.com/drive/folders/1gRMbk0bHvga3jxCXZMnDkV5L7J93Qxgt?usp=drive_link) | Charts and visualisations generated during analysis |
| 📑 [Presentation](https://drive.google.com/drive/folders/1iNvly8J3womehnxKehF4aIQhiE_qbgD1?usp=drive_link) | Board-ready slides with findings and recommendation |

## Key Analyses
- **Discount prevalence:** How many products are discounted, and how deeply?
- **Revenue impact:** Does discounting correlate with higher or lower revenue?
- **Seasonal patterns:** Do events like Black Friday and Christmas produce meaningful revenue spikes?

## Key Findings

**Discounting is structural, not tactical**
- 93% of products carry a discount  discounting has become the default state, not a promotional tool.
- Higher discount depth does not correlate with increased demand or revenue, undermining the core assumption behind the strategy.

**Seasonality, not discounts, drives revenue**
- Revenue spikes around Black Friday and Christmas are visible in the data, but they appear driven by seasonal demand rather than discount levels.

**Recommendation: Phase out blanket discounting**
- Remove across-the-board discounts and run controlled A/B tests to identify which discount strategies (if any) produce genuine uplift.
- Redirect discount spend toward targeted channels (e.g. newsletter sign-up offers) to attract and retain customers without eroding baseline margins.

## Key Learnings

**Data cleaning**
- Cleaning was not a footnote but a major part of the project, reducing the orders table from 226,614 to 40,985 rows through duplicate removal, missing value handling, and format filtering.
- Developed a systematic approach to documenting and justifying each cleaning decision.

**Python & Pandas**
- Moved from basic data manipulation to more targeted analytical queries, translating business questions directly into code.
- Practised structuring notebooks for readability and reproducibility.

**Communication**
- Distilling messy findings into a clear board narrative required as much thought as the analysis itself.

## Challenges Overcame
- **Data quality:** the dataset contained inconsistencies and gaps that required careful judgment calls about what to keep, fix, or exclude — and how to quantify the impact of those choices.

- **Telling a clear story:** with multiple competing findings, deciding what to emphasise in the board presentation was a genuine challenge.

## Author

**Henning** · [LinkedIn](https://www.linkedin.com/in/henning-ummethum/) · [GitHub](https://github.com/Ummethum)