# Customer Retention & Churn Analysis Dashboard
## Project Overview
This project focuses on analyzing customer retention and churn behavior to understand why customers leave a subscription-based business and what factors influence customer retention. The analysis was performed using Microsoft Excel, Power Query, Pivot Tables, Pivot Charts, and an interactive dashboard.
## Dataset Source
The dataset used for this project is the Telco Customer Churn Dataset, a widely used dataset for customer retention and churn analysis practice.
Dataset Link
(https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download)
## Data Cleaning & Transformation
Data cleaning and transformation were performed using Power Query Editor in Microsoft Excel.
 - Data Cleaning Steps
 - Removed duplicate customer records
 - Corrected incorrect data types
 - Removed errors and blank values
 - Standardized customer-related fields
 - Cleaned inconsistent entries
#### Data Transformation Steps
1. Created Tenure_Group
Customers were grouped based on subscription duration:
 - 0–1 Year
 - 1–2 Years
 - 2–4 Years
 - 4+ Years
Purpose : To analyze retention trends based on customer lifetime.
2. Created Charge_Category
Customers were categorized based on monthly charges:
 - Low
 - Medium
 - High
Purpose : To analyze customer spending behavior and churn patterns.
3. Created Customer_Status
Derived customer status from the churn column:
 - Churned
 - Retained
Purpose : To simplify retention and churn analysis.
## Dashboard Features
### The dashboard includes:
- Total Customers KPI
- Churned Customers KPI
- Retained Customers KPI
- Churn Rate KPI
- Retention Rate KPI
- Interactive Pivot Charts
- Dynamic Slicers
- Business-Oriented Visualizations
### Interactive Slicers Added
The dashboard includes interactive slicers for:
1 Customer Status
2 Contract Type
3 Tenure Group
4 Internet Service
These slicers allow dynamic filtering and real-time dashboard interaction.
## Business Insights Generated
The analysis provided several important business insights, including:
- Customers with month-to-month contracts showed the highest churn rate.
- Long-term customers were more likely to stay with the company.
- Fiber optic internet users had higher churn compared to DSL users.
- Customers using electronic check payment methods showed higher churn behavior.
- Customers with higher monthly charges showed increased churn risk.
- Customer retention improved significantly with increased tenure.
## Tools Used
- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Slicers
- Data Visualization
## conclusion

This project demonstrates how customer analytics and data visualization techniques can help businesses understand customer behavior, reduce churn, and improve customer retention.

Using Excel, Power Query, Pivot Tables, and interactive dashboards, raw customer data was transformed into meaningful business insights that support data-driven decision-making.
