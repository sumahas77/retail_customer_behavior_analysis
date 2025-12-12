📊 Retail Customer Behavior Analysis

A data analytics project exploring customer shopping behavior using Python, SQL, and Power BI.
The project covers end-to-end analysis—from data loading and cleaning to SQL business insights and dashboard creation.

🧠 Retail Customer Insights & Behavioral Analytics

📌 Overview

This project analyzes customer shopping behavior using a dataset of 3,900 retail transactions.
It includes data cleaning, EDA in Python, SQL-based business analysis, and a Power BI dashboard to deliver actionable insights.
The goal is to understand customer segments, revenue drivers, top-performing products, and behavior patterns.

📁 Dataset

Rows: 3,900
Columns: 18

Data Includes:

Customer demographics: age, gender, subscription status

Purchase details: item, category, amount, season, size, color

Behavior attributes: discount usage, review rating, shipping type, previous purchases

🛠️ Tools & Technologies

Python (pandas, numpy, seaborn, matplotlib)

Jupyter Notebook

PostgreSQL / SQL

SQLAlchemy for DB connection

Power BI for dashboard

Gamma for presentation creation

🔍 Steps in the Project
1. Data Loading

Loaded dataset using pandas

Initial structure check with .info() and .describe()

2. Data Cleaning

Imputed missing review ratings using category-wise median

Converted column names to snake_case

Removed redundant fields (promo_code_used)

3. Exploratory Data Analysis (EDA)

Visualized customer demographics

Analyzed purchase behavior and discount patterns

Created age_group and purchase_frequency_days

4. SQL Business Analysis

Connected cleaned data to PostgreSQL and executed queries to extract insights:

Revenue by gender

High-spending discount users

Top 5 products by average review rating

Standard vs. express shipping comparison

Subscribers vs. non-subscribers

Discount-dependent products

Customer segments (New, Returning, Loyal)

Top 3 products per category

Revenue contribution by age groups

5. Dashboard Creation

Built a Power BI dashboard to visualize:

Sales and revenue trends

Customer segments

Most purchased products

Shipping and discount behavior

6. Presentation

A summary presentation was created using Gamma to highlight insights, results, and recommendations.

📈 Results / Key Outcomes

One gender group generated higher total revenue, indicating a strong customer segment.

Many customers used discounts but still spent above average, proving they are high-value buyers.

The top-rated products showed strong customer satisfaction and higher purchase frequency.

The top 3 best-selling items in each category drove most category-level sales.

Subscribers spent more and purchased more often, proving the effectiveness of subscription plans.

💡 Business Recommendations 

Enhance subscription benefits to increase conversion and retention.

Promote top-rated and best-selling products to drive more sales.

Optimize discount strategy for discount-heavy products to improve margins.

Target high-value segments (adult/middle-aged, high-spending gender group, express shipping users)
