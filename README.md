# E-Commerce Health Check — Olist

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to evaluate the health of an online retail business.

## Objectives

- Analyze order values and revenue
- Identify top products by revenue
- Calculate repeat customer rate
- Analyze monthly order trends
- Study shipping time and customer review scores
- Detect order-value outliers
- Calculate a 95% confidence interval for average order value
- Compare weekday and weekend order volumes

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- SciPy
- Jupyter Notebook

## Key Findings

- Average Order Value: **160.58**
- 95% Confidence Interval: **159.21 to 161.95**
- Repeat Customer Rate: **3.12%**
- Shipping Time vs Review Score Correlation: **-0.334**
- Weekday Orders: **76,594**
- Weekend Orders: **22,847**
- Order-Value Outliers: **7,775**
- Outlier Percentage: **7.88%**

## SQL Analysis

The project uses SQL queries with:

- JOIN
- GROUP BY
- CTE
- Window Function (`RANK()`)

The analysis covers product revenue, repeat customers, monthly order trends, and product ranking.

## Business Recommendation

The retailer should focus on improving delivery performance and customer retention. Loyalty programs, personalized promotions, and post-purchase engagement can help encourage repeat purchases. High-value orders should also be monitored separately because they can significantly affect revenue metrics.

## Conclusion

The E-Commerce Health Check provides insights into revenue, customer retention, delivery performance, customer satisfaction, and order-value patterns.
