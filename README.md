# Consumer Purchasing Behavior Analysis

## Project Overview

This project analyzes retail sales and customer purchasing behavior using SQL and Microsoft Power BI. The dashboard provides insights into revenue trends, profitability, customer demographics, and product category performance to support business decision-making.

The goal of this project was to transform raw retail transaction data into interactive business intelligence visuals and actionable insights.

---

## Tools & Technologies

* SQL
* Microsoft Power BI
* DAX Measures
* Data Cleaning & Transformation
* Data Visualization

---

## Dashboard Features

* Revenue analysis by product category
* Profitability analysis by category
* Monthly revenue trend analysis
* Customer demographic analysis by gender
* Interactive year/quarter filtering

---

## Key Insights

* Clothing generated the highest sales volume among all categories.
* Revenue distribution across categories was relatively balanced, indicating diversified product performance.
* Revenue between male and female customers was nearly evenly split, suggesting broad customer appeal.
* Monthly sales trends showed fluctuations that may indicate seasonality or promotional impacts.
* Profit analysis revealed differences between revenue generation and profitability across categories.

---

## DAX Measures Used

### Profit

```DAX
Profit =
SUM('sql_project_p1 retail_sales'[total_sale]) - SUM('sql_project_p1 retail_sales'[cogs])
```

### Revenue Total

```DAX
Revenue Total = SUM('sql_project_p1 retail_sales'[total_sale])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE( [Profit], [Revenue Total])
```

---

## Dashboard Preview

Screenshot in file named Dashbiard SS.png

---

## Files Included

* Retail sales SQL analysis script
* Power BI dashboard (.pbix)
* Dashboard screenshots
* README documentation

---

## Future Improvements

* Add customer age segmentation analysis
* Add shift/time-of-day sales analysis
* Add repeat customer analysis
* Create KPI cards and forecasting visuals

---

## Author

Kevon Kidd
