📊 Customer Shopping Behavior Analysis
🔹 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to understand spending patterns, customer segments, product preferences, and subscription behavior to support better business decisions.

🔹 Dataset Summary
Rows: 3,900
Columns: 18
Key Features:
Customer demographics: Age, Gender, Location, Subscription Status
Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type
Missing Data: 37 values in the Review Rating column
🔹 Data Cleaning & Preparation (Python)

Data was cleaned and prepared using Python and Pandas:

Loaded and explored data using pandas, .info(), and .describe()
Handled missing values by imputing Review Rating using median values by category
Standardized column names into snake_case for consistency
Performed feature engineering:
Created age_group for segmentation
Created purchase_frequency_days
Removed redundant column (promo_code_used) after consistency check
Loaded cleaned data into PostgreSQL for further analysis
🔹 Data Analysis (SQL)

Performed SQL analysis in PostgreSQL to answer key business questions:

Compared revenue by gender
Identified high-spending customers using discounts
Found top-rated products
Analyzed shipping type impact on spending
Compared subscribers vs. non-subscribers
Identified discount-dependent products
Segmented customers into New, Returning, and Loyal
Analyzed top products per category
Studied repeat buyers and subscription behavior
Evaluated revenue contribution by age group
🔹 Dashboard (Power BI)

Built an interactive Power BI dashboard to visualize insights, including:

Sales and revenue trends
Customer segmentation
Product performance
Subscription and purchasing behavior
🔹 Key Insights
Loyal and repeat customers contribute significantly to revenue
Certain products rely heavily on discounts to drive sales
Subscribers tend to show more consistent purchasing behavior
Specific age groups and shipping preferences generate higher revenue
🔹 Business Recommendations
Promote subscription programs with exclusive benefits
Introduce loyalty rewards to retain repeat customers
Optimize discount strategies to balance revenue and profit
Highlight top-rated and best-selling products in marketing campaigns
Use targeted marketing based on customer segments and behavior
🔹 Tools Used
Python (Pandas)
PostgreSQL (SQL)
Power BI
