# Revenue Leakage Analysis for an E-Commerce Business

## Problem Statement

The business appears to be growing as new customers continue to place orders and revenue is being generated consistently. However, this growth has started to feel unstable. Even though sales numbers look healthy, there is uncertainty around how much of this revenue is sustainable in the long run.

Management believes that revenue may be leaking through everyday issues such as poor customer retention, weak delivery experience, and operational failures. These problems are not obvious at first glance but can quietly slow down long term business growth if ignored.

## Objective

The objective of this analysis is **to identify where revenue is leaking** across the business, quantify the impact of each leakage area, and highlight which issues need immediate attention to stabilize and improve revenue growth.

## Dataset Overview

This analysis uses a public E Commerce dataset that captures end to end order activity.

**Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Analysis and Key Insights

### Stage 01 : Customer Behavior Leakage

This stage focuses on understanding how customer purchasing patterns impact revenue sustainability, especially repeat purchases.

**Insights:**

- **97% of customers** are one time buyers
- **94.4% of total revenue** comes from one time buyers
- Average revenue per repeat customer is **nearly 2 times higher** than one time customers

Clear evidence of **revenue leakage** due to weak customer retention.

### Stage 02 : Experience Driven Leakage

This stage evaluates how delivery delays and poor experience affect customer satisfaction and future revenue.

**Insights:**

- **8.11% of orders** were delivered later than expected, affecting `8.32%` of customers
- **8.76% of total revenue**, worth **1.35 million** is associated with delayed deliveries
- Average review score drops from `4.29` for on time deliveries to `2.56` for late deliveries

Poor experience is strongly linked to **revenue at risk**.

### Stage 03 : Operational and Seller Side Leakage

This stage analyzes revenue loss caused by internal operational failures and seller performance.

**Insights:**

- **143 thousand** revenue is directly lost due to order cancellations
- Only **4 sellers** consistently cause delivery delays
- Revenue linked to poor seller performance is very small compared to total delayed delivery revenue
- Top sellers contribute only **12.9%** of total revenue

Revenue leakage is primarily **operational**, with cancellations being the most concerning loss area.

## Recommendations

- Improve customer retention through better post purchase engagement and repeat purchase incentives
- Focus on fixing operational delivery issues rather than broadly targeting sellers
- Reduce order cancellations by improving inventory planning and order fulfillment coordination

## Conclusion

The analysis shows that **revenue leakage is driven more by execution gaps than demand issues**. Customer retention and delivery experience pose the highest risk to sustainable growth, while seller dependency and seller driven delays are limited. Addressing operational inefficiencies and improving customer experience can significantly improve long term revenue stability.

Project by [**Anurag Chauhan**](https://www.linkedin.com/in/theanuragchauhan/)
