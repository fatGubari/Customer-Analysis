# Customer Analysis

## Project Overview
An end-to-end customer analysis project using SQL and Python to understand customer purchasing behavior, customer segmentation, repeat purchases, and retention.

## Dataset
Online Retail II — UCI Machine Learning Repository.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite3
- SQL

## Project Objectives
- Understand customer purchasing behavior.
- Identify high-value customers.
- Perform RFM customer segmentation.
- Calculate repeat purchase rates.
- Analyze purchase frequency.
- Calculate time between purchases.
- Perform customer cohort analysis.
- Evaluate customer retention.

## Project Workflow
1. Data collection
2. Data exploration
3. Data cleaning
4. SQL customer analysis
5. RFM segmentation
6. Repeat purchase analysis
7. Cohort retention analysis
8. Business insights and recommendations

## Key Metrics
- Total Customers
- Total Orders
- Average Customer Spending
- Average Orders per Customer
- Repeat Purchase Rate
- Customer Recency
- Customer Frequency
- Customer Monetary Value
- Customer Retention Rate

## Key Findings
- Customer Base & Repeat Behavior: Out of 4,307 total customers, 2,893 (67.17%) are repeat buyers.
- Top Segments: Champions (1,084 customers) are our most valuable and active group, averaging 10.52 orders and $5,337.86 in revenue per customer, followed by Loyal Customers (315 customers) averaging 6.12 orders.
- Churn Risk: Lost Customers (1,025 customers) have largely stopped purchasing, averaging only 1.13 orders and 212.49 days since their last purchase.
- Return Timing: Repeat buyers take an average (mean) of 38.44 days between orders, while the typical (median) return gap is 20–21 days (the mean is pulled up by customers with unusually long gaps).

## Business Recommendations
- Target Potential Loyalists for Repeat Conversion: Run targeted second-order incentives or bundle offers for Potential Loyalists (verify exact segment count in your RFM table) to move them into Loyal Customers without eroding full-price margins.
- Accelerate Second Purchases for New / One-Time Buyers: Send a timed follow-up offer or personalized recommendation before the typical return window closes (20–38 days) so first-time buyers do not drift into Lost Customers.
- Use Low-Cost Win-Backs for Lost Customers (1,025): Test lightweight reactivation messages on Lost Customers (and early outreach for At Risk buyers) using a control/holdout group rather than costly across-the-board discounts.
- Protect Margin With Champions Instead of Blanket Discounts: Avoid giving across-the-board discount codes to all segments; reward Champions with exclusive perks, early access, or loyalty points while keeping promotional spend focused on conversion and retention gaps.
- Address Monthly Cohort Drop-Off: Focus retention efforts on the early drop-off after a customer's first purchase month and monitor cohort curves by month and order number to see whether targeted follow-ups lift Month-2 and Month-3 retention.  

## Visualizations
- Customer Segmentation
- Purchase Intervals By Customer Segment
- Days Between Purchases
- Customer Retention Heatmap

## Author
Data Analyst Portfolio Project By Fatima Abdullah
