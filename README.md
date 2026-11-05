# E-Commerce Sales & Customer Analysis (Olist, 2017-2018)

**Live dashboard:** https://public.tableau.com/app/profile/bhuvaneshwari.d8406/viz/OlistE-CommerceSalesAnalysis_17938565139620/E-CommerceSalesCustomerAnalysisOlist2017-2018

## Business problem
An online marketplace wants to understand what drives revenue, why some
customers leave bad reviews, and how delivery performance affects satisfaction.

## Data
Brazilian E-Commerce Public Dataset by Olist (Kaggle): about 99k orders
across 9 tables. Analysis period: Jan 2017 - Aug 2018 (2016 and Sep-Oct 2018
excluded because the data is incomplete).

## Tools
Python (Pandas, Matplotlib), Jupyter Notebook, Tableau Public, SQL-style joins

## Key findings
1. Orders grew about 9x from Jan to Nov 2017, peaking in Nov 2017 (7,544 orders).
2. Health & beauty leads revenue (R$1.26M), while bed_bath_table leads volume.
   Watches & gifts rank #2 by revenue but #8 by volume due to high price per item.
3. São Paulo contributes 38.3% of total revenue.
4. Late deliveries (6.8% of orders) are associated with an average review score
   of 2.27 vs 4.29 for on-time orders.
5. Only 3.1% of customers made a repeat purchase, so growth depends on
   acquiring new customers.

## Recommendation
Improve delivery reliability and retention offers. Late delivery is associated
with low reviews, which likely hurts repeat purchases (hypothesis, not tested).

## Data quality notes
- 1.4% of items had no category and were labelled "unknown".
- Undelivered orders were excluded from delivery and review analysis.

## Files
- `01_data_loading.ipynb`: cleaning, analysis and charts
- Raw CSV files are not included (download from Kaggle)