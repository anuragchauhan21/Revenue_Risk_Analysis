# Revenue Risk Analysis

**Analyzing customer retention, delivery performance, and operational risks impacting revenue stability in an e-commerce business.**

## Overview

This project evaluates factors that put current and future revenue at risk using transaction-level e-commerce data.

The analysis focuses on three business areas:

* Customer Retention
* Delivery Performance
* Operational Efficiency

The objective is to identify revenue risks, quantify their impact, and prioritize the areas with the greatest potential to improve revenue stability.

## Problem Statement

The business continues to generate revenue and acquire customers, but management needs to understand whether growth is sustainable.

This analysis investigates whether customer retention challenges, delivery performance issues, or operational inefficiencies are creating risks to future revenue growth.

## Objective

* Quantify key sources of revenue risk across the business.
* Evaluate the impact of customer retention, delivery performance, and operational issues.
* Identify areas that should be prioritized to improve revenue stability.

## Dataset Overview

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

The dataset contains end-to-end order lifecycle information across multiple tables:

`customers` ▪ `location` ▪ `order_items` ▪ `payments` ▪ `reviews` ▪ `orders` ▪ `product` ▪ `seller` ▪ `product_category`

The 9 CSV files were structured into a relational SQLite database to enable multi-table analysis using SQL.

## Tools and Technologies

`Python` ▪ `SQL` ▪ `SQLite` ▪ `Pandas` ▪ `Matplotlib` ▪ `Seaborn` ▪ `Jupyter Notebook`

## Methods

1. Built a relational SQLite database from raw CSV files.
2. Validated data quality through missing value, duplicate, and integrity checks.
3. Performed multi-table SQL analysis across customers, orders, payments, reviews, products, and sellers.
4. Evaluated customer retention patterns and revenue contribution.
5. Assessed delivery performance, customer experience impact, and revenue exposure.
6. Analyzed operational risks including order cancellations.
7. Visualized findings using Python.

## Analysis and Key Insights

### Stage 01: Customer Retention

#### Findings

* Repeat customers generated nearly `2x` higher revenue per customer than one-time buyers.
* Increasing repeat purchase rates to `5%` could unlock approximately `₹0.58M` in additional revenue.
* Increasing repeat purchase rates to `10%` could generate more than `₹2.0M` in additional revenue.
* Revenue growth remains heavily dependent on acquiring new customers.

#### Recommendation

* Prioritize initiatives that increase second-order conversion and repeat purchasing behavior.


### Stage 02: Delivery Performance

#### Findings

* `8.11%` of delivered orders arrived later than the promised delivery date, affecting `8.32%` of customers.
* Delayed deliveries were associated with `₹1.35M` in revenue, representing `8.76%` of total revenue.
* Average customer ratings declined from `4.29` to `2.57` when deliveries arrived late.
* Nearly `50%` of delayed-delivery revenue exposure was concentrated in just `SP` and `RJ`.

#### Recommendation

* Prioritize logistics improvements in high-exposure states to reduce delivery-related revenue risk and improve customer experience.


### Stage 03: Operational Efficiency

#### Findings

* Order cancellations resulted in approximately `₹0.14M` in direct revenue loss.
* Cancellation rates remained below `1%` across major states.
* No meaningful geographic concentration of cancellations was identified.

#### Recommendation

* Investigate order-level drivers of cancellations, including fulfillment and operational issues, rather than focusing on specific regions.

## Conclusion

The analysis identified customer retention and delivery performance as the primary sources of revenue risk.

Revenue growth remains heavily dependent on first-time buyers, while delayed deliveries expose a meaningful share of revenue to customer experience issues and are concentrated within a small number of states.

In contrast, cancellation-related losses are relatively limited and do not appear to be driven by geographic concentration.

Overall, the findings indicate that improving retention and delivery execution offers the greatest opportunity to strengthen revenue stability and support sustainable growth.

### Author

[Anurag Chauhan](https://www.linkedin.com/in/theanuragchauhan/)
