# Ecommerce Discount Strategy Analysis
Data analysis project investigating whether discounts help or hurt an e-commerce company. Covers discount depth, seasonal sales patterns (Black Friday, Christmas), product categorization, and price distribution. Presented to a simulated company board.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![VS Code](https://img.shields.io/badge/VS%20Code-IDE-blue)

---

## The Business Problem

Eniac, a growing e-commerce company, is caught in an internal debate.
The Marketing team believes discounts drive customer acquisition and long-term
growth. The Board worries that aggressive pricing is quietly eroding revenue.
Both sides have a point. Neither has the data to prove it.

That is where we came in.

---

## What We Did

We worked with four interconnected internal CSV files covering orders,
orderlines, products, and brands. The data was real, messy, and unfiltered,
which meant data cleaning was not a footnote but a major part of the project.

From there, we moved into analysis, tackling questions like:

- How many products are being discounted, and how deeply?
- Do seasons and events like Black Friday or Christmas move the needle on revenue?
- How can products be grouped into meaningful categories for cleaner reporting?

The final output was a concise board presentation with a clear, evidence-based
recommendation.

---

## Tools and Stack

| Purpose              | Tool          |
|----------------------|---------------|
| Data manipulation    | Python, Pandas|
| Visualization        | Seaborn, Matplotlib       |
| Development environment | VS Code + Jupyter Notebooks |

---

## Repository Structure
```
.
├── cleaned_csv/            # cleaned datasets
├── code/                   # Jupyter notebooks
├── original_csv/           # original datasets
├── plots/                  # plots generated during the analysis
├── presentation/           # final board presentation
├── quality_assured_csv/    # quality assured datasets
└── README.md
```


---
## Getting Started

Clone the repo and install the dependencies:

```bash
git clone https://github.com/Ummethum/ecommerce-discount-strategy-analysis.git
cd ecommerce-discount-strategy-analysis
pip install pandas seaborn matplotlib
```

Then open any notebook in the `code/` folder with Jupyter in VS Code
and run the cells from top to bottom.

---

## Contributors

This was a team effort. Thanks to everyone who shaped the analysis 
and put together the final presentation:

- Malynn Buranawichian
- Shannon Martin
- Paul Anderson
- Henning Ummethum