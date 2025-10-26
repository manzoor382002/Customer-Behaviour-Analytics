# Customer Shopping Behavior Analysis

This project aims to analyze customer shopping behavior to help a retail company improve sales, customer satisfaction, and long-term loyalty by identifying purchasing trends and business improvement opportunities.

## Business Problem

A retail company wants to understand customer behavior changes across:

- Demographics
- Product categories
- Discounts and reviews
- Seasonal trends
- Purchase frequency
- Subscription status

Key business questions:

- What factors influence customers to buy more?
- How can repeat purchases and loyalty be increased?
- How to optimize marketing, discount strategies, and product placement?

## Dataset Summary

- Total Records: 3,900
- Total Columns: 18
- Includes:
  - Age, Gender, Location, Subscription Status
  - Item Purchased, Category, Season, Size, Color
  - Purchase Amount, Review Rating
  - Discount Applied, Shipping Type, Previous Purchases
- Missing Data: 37 missing values in Review Rating

## Data Preparation and Feature Engineering (Python)

- Loaded dataset using pandas for initial exploration
- Handled missing values by imputing median review rating per category
- Standardized column names using snake_case format
- Feature Engineering:
  - Created age_group by binning ages
  - Created purchase_frequency_days based on purchase history
- Removed redundant column: promo_code_used
- Stored cleaned dataset in PostgreSQL for SQL analysis

## SQL Analysis (Business Insights)

SQL queries were executed to analyze:

- Revenue by gender
- High-spending customers using discounts
- Top 5 highest-rated products
- Average revenue by shipping type (Express vs Standard)
- Purchase behavior of Subscribers vs Non-Subscribers
- Most discount-dependent product categories
- Customer segmentation:
  - New customers
  - Returning customers
  - Loyal customers
- Top 3 most purchased products per category
- Subscription likelihood among repeat buyers
- Revenue contribution by each age group

## Power BI Dashboard Insights

The dashboard visualizes:

- Revenue trends
- Product performance
- Customer segments
- Subscription behavior
- Shipping preferences
- Seasonal purchase behavior

## Business Recommendations

- Increase subscription benefits to boost recurring revenue
- Introduce loyalty rewards for repeat customers
- Promote top-rated and best-selling products in campaigns
- Focus marketing efforts on high-value age groups
- Optimize discount strategies to balance profit and demand

## Project Deliverables

- Python scripts for data cleaning and transformation
- SQL queries and result analysis
- Power BI interactive dashboard
- Final report and business insight presentation
- Structured GitHub repository

## Tools and Technologies

- Python (pandas, numpy)
- PostgreSQL
- Power BI
- Git and GitHub

## Conclusion

The analysis supports data-driven decision-making, helping the company improve customer engagement, optimize product and marketing strategies, and increase long-term revenue and loyalty.

