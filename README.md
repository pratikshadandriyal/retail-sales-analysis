# 🛒 Retail Sales Analysis — Python + Pandas

## Business Problem
A retail company needed clarity on category performance, monthly revenue trends, 
and return rate impact before a management review meeting.

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook

## Dataset
- 500 rows of synthetic retail transaction data (2024–2025)
- 9 columns: order details, category, pricing, discount, region, returns

## What I Did
1. **Data Audit** — identified missing values, wrong dtypes, invalid dates, negative prices
2. **Data Cleaning** — dropped 30 invalid rows, filled missing discounts with 0 (business assumption)
3. **Feature Engineering** — created `revenue` column accounting for discounts
4. **Analysis** — answered 3 business questions using groupby aggregations
5. **Visualisation** — 3 charts mapping directly to each business question

## Key Findings
| Finding | Detail |
|---|---|
| Top category by revenue | Groceries — ₹15.1L (138 orders) |
| Highest avg order value | Electronics — ₹12,803 per order |
| Peak month | July 2024 |
| Returns risk | 10.8% of total revenue |

## Business Recommendations
1. Investigate Furniture — lowest volume and lowest revenue across all categories
2. Analyse July conditions — was there a promotion or seasonal driver?
3. Set a return rate threshold alert if it crosses 15%

## Files
| File | Description |
|---|---|
| `retail_sales_analysis.ipynb` | Main analysis notebook |
| `retail_sales.csv` | Raw dataset |
| `retail_sales_clean.csv` | Cleaned dataset |
| `retail_sales_analysis.png` | Summary charts |
