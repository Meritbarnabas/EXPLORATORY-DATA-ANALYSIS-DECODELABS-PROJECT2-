# EXPLORATORY-DATA-ANALYSIS-DECODELABS-PROJECT2-
Project Overview :

This repository contains an Exploratory Data Analysis (EDA) conducted on a transactional dataset to extract key business insights, identify statistical baselines, detect anomalies, and provide strategic recommendations for optimizing revenue and operational efficiency.

📊 Dataset Overview
The dataset analyzed consists of **1,200 rows and 14 columns** after data cleaning. It tracks e-commerce transaction metrics including product types, pricing, cart items, order statuses, and marketing referral channels.

1. Descriptive Statistics Overview
According to the data detailed in "EDA_Report.docx", the cleaned dataset spans 1,200 rows and 14 columns, revealing key baseline transaction metrics:

Items in Cart: The dataset shows an average of 5.48 items per transaction, with a median of 5.0.
Quantity Purchased: Purchases typically average about 2.95 units per order.

Unit Price: Product pricing centers around an average of 356.41.

Total Price: Reflects an overall transaction mean of 1,053.97, with a median of 823.62.

3. Outlier Detection
Using the Interquartile Range (IQR) method, 8 high-value outlier transactions were identified in TotalPrice. Any order value extending above 3,330.41 is considered an outlier.
The top outlier transactions from the report include:
ORD200789 (Tablet): 3,456.4

ORD201122 (Monitor): 3,390.95

ORD200632 (Laptop): 3,390.8

ORD200469 (Chair): 3,384.9

ORD200328 (Tablet): 3,370.2

5. Key Insights
Channel Performance: Instagram generated the highest overall total revenue, while Facebook led the way in driving the highest average order value.

Operational Hurdles: Cancelled and returned orders are relatively high, signaling potential challenges in logistics, delivery communication, or customer satisfaction.

Top Revenue Drivers: Chair, Printer, and Laptop categories yielded the highest revenue and should remain priority focus areas.

Underperforming Sectors: Phone and Desk categories brought in comparatively lower revenue numbers.

Outlier Patterns: High-value transaction outliers are predominantly tied to premium product selections purchased at maximum quantities.

7. Strategic Recommendations
Optimize Operations: Reduce costly cancellation and return rates by improving delivery communication and refining product quality checks.

Scale High-ROI Marketing: Increase investment in high-performing referral channels such as Instagram and Facebook.

Leverage Core Products: Promote top-selling categories using dedicated loyalty discounts and cross-selling campaigns.

Investigate Outliers: Analyze high-value outlier transactions to isolate potential VIP customers or bulk purchase opportunities.
