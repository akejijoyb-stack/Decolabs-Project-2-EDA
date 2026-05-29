# Decolabs-Project-2-EDA
📌 Project Overview

This project focused on performing Exploratory Data Analysis (EDA) on an e-commerce dataset to uncover trends, patterns, distributions, and outliers within the data.

The objective was to move beyond simple reporting and use analytical techniques to understand customer purchasing behavior, product performance, operational patterns, and revenue distribution.

🎯 Objectives

The major objectives of this project include:

Calculate descriptive statistics such as:
Mean
Median
Count
Identify revenue and product trends
Analyze customer transaction behavior
Detect outliers within the dataset
Summarize meaningful business insights from the data

🛠️ Tools Used
Microsoft Excel
Pivot Tables
Excel Charts

📂 Dataset Description

The dataset contains transactional e-commerce records with the following columns:

Order ID
Date
Customer ID
Product
Quantity
Unit Price
Shipping Address
Payment Method
Order Status
Tracking Number
Items in Cart
Coupon Code
Referral Source
Total Price

📁 Repository Structure
Project-2-EDA/
│
├── data/
│   └── cleaned_dataset.xlsx
│
├── images/
│   ├── descriptive_statistics.png
│   ├── revenue_trend.png
│   ├── product_quantity_trend.png
│   ├── revenue_by_product.png
│   ├── payment_method_analysis.png
│   ├── order_status_analysis.png
│   ├── referral_source_analysis.png
│   └── outlier_analysis.png
│
├── analysis.xlsx
└── README.md

Descriptive Statistics

Descriptive statistics were calculated to summarize the central tendency and overall distribution of the dataset.

Metric	Value
Total Orders (Count)	1,200
Average Order Value (Mean)	$1,053.97
Highest Transaction Value	$3,456.4
Key Observations
The dataset contains a total of 1,200 customer transactions.
The average order value was approximately $1,053.97, indicating moderate customer spending behavior across transactions.
Revenue values showed moderate variation, with a few high-value transactions significantly exceeding the average order value.

Descriptive Statistics Screenshot
<img width="1365" height="730" alt="Statistic" src="https://github.com/user-attachments/assets/6c39d946-bb0d-4b8d-baf8-d6915bb1971e" />


📈 Revenue Trend Analysis

A revenue trend analysis was conducted using pivot tables to evaluate sales performance across different years and months.

Key Findings
Revenue was highest in 2023, generating approximately $552.6K in sales.
Revenue declined slightly in 2024 to approximately $480.2K.
The 2025 dataset contains partial-year data, resulting in lower total recorded revenue.
Revenue increased progressively from January to June 2025, indicating improved sales activity during the observed period.
June recorded the highest monthly revenue in 2025.
<img width="1365" height="728" alt="Revenue trend" src="https://github.com/user-attachments/assets/c6a5efe6-b774-46d2-8690-b02567ab380a" />


📦 Product Quantity Trend Analysis

A product trend analysis was performed using the quantity sold across different product categories.

Key Findings
Chairs recorded the highest quantity sold with 562 units.
Printers and laptops also demonstrated strong customer demand.
Phones recorded the lowest quantity sold among all product categories.
Product demand remained relatively balanced across categories.
Product Quantity Trend Screenshot
<img width="1365" height="577" alt="Products Trend" src="https://github.com/user-attachments/assets/8dc4361a-4d17-4d35-ab7d-e47fc936fad9" />


💰 Revenue by Product Analysis

A product revenue analysis was conducted to evaluate the contribution of each product category to total sales revenue.

Key Findings
Chairs generated the highest revenue at approximately $197.6K.
Printers and laptops also contributed significantly to overall revenue.
Phones generated the lowest revenue among all product categories.
Revenue distribution across products remained relatively balanced.
Revenue by Product Screenshot
<img width="1360" height="729" alt="Revenue by product" src="https://github.com/user-attachments/assets/8c8dbabd-2365-49ed-ad30-042e5b496044" />


💳 Payment Method Analysis

A payment method analysis was conducted to understand customer transaction preferences.

Key Findings
Online payments were the most commonly used transaction method with 258 orders.
Cash payments followed closely behind with 246 transactions.
Credit card, debit card, and gift card transactions showed relatively balanced usage levels.
Customer transactions were distributed across multiple payment channels.
📷 Payment Method Screenshot
<img width="1365" height="723" alt="Payment Trend" src="https://github.com/user-attachments/assets/81ed0a3c-a061-4e5c-ae52-9787e25f0232" />

📦 Order Status Analysis

An order status analysis was conducted to evaluate fulfillment performance and transaction completion patterns.

Key Findings
Cancelled orders recorded the highest transaction count with 250 orders.
Returned orders were also significantly high at 247 transactions.
Pending and shipped orders accounted for a substantial portion of total transactions.
Delivered orders recorded relatively lower counts compared to cancelled and returned orders.
The distribution of order statuses suggests potential operational inefficiencies or fulfillment challenges.
📷 Order Status Screenshot
<img width="1365" height="725" alt="Order status" src="https://github.com/user-attachments/assets/18625c48-2e7d-4e9a-becf-6955a76292c3" />


📣 Referral Source Analysis

A referral source analysis was conducted to evaluate customer acquisition channels based on generated revenue.

Key Findings
Instagram generated the highest revenue contribution at approximately $275.3K.
Email campaigns also contributed strongly to total revenue generation.
Google and Facebook generated relatively similar revenue contributions.
Referral traffic recorded the lowest revenue contribution among all channels.
Revenue generation across referral channels remained relatively balanced.
📷 Referral Source Screenshot
<img width="1364" height="716" alt="Referral Source" src="https://github.com/user-attachments/assets/17cf41f0-3af2-4d56-a72e-6b8d3ccd9d06" />

🚨 Outlier Analysis

An outlier analysis was conducted using the Total Price variable to identify unusually high transaction values.

Key Findings
The average order value across the dataset was approximately $1,053.97.
Most transactions remained within a moderate price range.
The highest observed transaction value was approximately $3,353.75, which is more than three times higher than the average order value.
These high-value transactions indicate the presence of revenue outliers within the dataset.
The identified outliers may represent bulk purchases, premium customers, or unusually large orders.
📷 Outlier Analysis Screenshot
<img width="1363" height="725" alt="Outlier Analysis" src="https://github.com/user-attachments/assets/6bb02ff0-1448-4b80-a6f6-69decd80643c" />

💡 Overall Insights
Customer spending patterns remained relatively stable across the dataset.
Chairs consistently demonstrated strong performance in both quantity sold and revenue generated.
Instagram emerged as the strongest-performing referral channel.
Payment methods showed balanced customer adoption across multiple transaction options.
High cancellation and return rates may indicate operational or customer satisfaction challenges.
Revenue outliers contributed disproportionately to total sales performance.

📌 Conclusion

The exploratory data analysis successfully uncovered key trends, patterns, and operational insights within the dataset. Product performance, customer transaction behavior, referral effectiveness, and revenue distribution were evaluated using descriptive statistics and pivot table analysis. The project also identified operational concerns, such as high cancellation and return rates, as well as high-value transaction outliers. These findings provide a strong analytical foundation for future dashboard development and advanced business intelligence analysis.

👨‍💻 Author

Joy Akeji
DecodeLabs Data Analytics Internship – Batch 2026
