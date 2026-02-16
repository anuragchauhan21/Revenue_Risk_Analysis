# Revenue Leakage Analysis for an E-Commerce Business

## Problem Statement

The business is generating consistent revenue and attracting new customers. However, there are concerns about the stability and long-term sustainability of this growth.

Management wants to examine whether revenue is being affected by gaps in customer retention, delivery performance, or operational processes, and assess the overall impact on business growth.

## Objective

The objective of this analysis is to **identify where revenue is leaking** across the business, quantify the impact of each leakage area, and highlight which issues need immediate attention to stabilize and improve revenue growth.

## Dataset Overview

This analysis uses a public E Commerce dataset that captures end to end order activity.

**Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

> The `9 csv` files were structured into a relational SQLite database, enabling multi-table joins and revenue analysis using SQL queries.

## Analysis and Key Insights

### Stage 01 : Customer Behavior Leakage

This stage focuses on understanding how customer purchasing patterns impact revenue sustainability, especially repeat purchases.

**Insights:**

- **97% of customers** are one time buyers
- **94.4% of total revenue** worth **14.5M** comes from one time buyers
- Average revenue per repeat customer is **nearly 2 times higher** than one time customers

> Revenue is acquisition-driven rather than retention-driven, increasing long-term dependency on continuous customer acquisition.

### Stage 02 : Experience Driven Leakage

This stage evaluates how delivery delays and poor experience affect customer satisfaction and future revenue.

**Insights:**

- **8.11% of orders** were delivered later than expected, affecting `8.32%` of customers
- **8.76% of total revenue**, worth **1.35 million** is associated with delayed deliveries
- Average review score drops from `4.29` for on time deliveries to `2.56` for late deliveries

> Late deliveries significantly reduce review scores, indicating potential risk to future customer retention.

### Stage 03 : Operational and Seller Side Leakage

This stage analyzes revenue loss caused by internal operational failures and seller performance.

**Insights:**

- **0.14 million** revenue is directly lost due to order cancellations
- Only **4 sellers** consistently cause delivery delays
- Revenue linked to poor seller performance is very small compared to total delayed delivery revenue
- Top sellers contribute only **12.9%** of total revenue

> Direct revenue loss from cancellations exceeds revenue concentration risk from seller-driven delays.

## Data-Driven Action Points

- Since 94.4% of revenue comes from customers who purchase only once, the business should track how many customers place a second order and focus on increasing repeat purchases.
- Instead of reviewing all sellers, closely monitor the 4 sellers who regularly cause delivery delays and take corrective action there.
- Analyze why orders are being cancelled and add better checks before dispatch to prevent avoidable revenue loss.

## Conclusion

Revenue growth is largely driven by first-time buyers, while a measurable share of revenue is exposed to delivery delays and cancellations.

The analysis shows that revenue stability depends not only on sales volume but on improving retention and operational consistency.

Addressing these gaps can convert unstable revenue into sustainable growth.

---

Project by [**Anurag Chauhan**](https://www.linkedin.com/in/theanuragchauhan/)
