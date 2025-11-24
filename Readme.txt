📊 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using 3,900 transactional records across multiple product categories.
The objective is to understand customer spending patterns, product preferences, discount usage, subscription behavior, and demographic insights to support business decision-making.

The workflow covers Python-based data cleaning, SQL-based business analysis, and an interactive Power BI dashboard for visualization.

🎯 Objectives

Analyze customer purchase patterns and spending trends

Segment customers into actionable groups (New, Returning, Loyal)

Compare behavior of subscribers vs non-subscribers

Identify top-performing products and discount-dependent items

Understand revenue contribution by demographics (age, gender)

Build an interactive Power BI dashboard for stakeholders

Provide data-driven business recommendations

📁 Dataset Summary

Rows: 3,900

Columns: 18

Missing Values: 37 missing entries in review_rating

Key Features Include:

Demographics: age, gender, location, subscription_status

Purchase Details: item_purchased, category, purchase_amount, season

Behavior Indicators: discount_applied, previous_purchases, shipping_type

🛠️ Tech Stack
Languages & Tools

Python (Pandas, NumPy, Matplotlib)

PostgreSQL

Jupyter Notebook

Power BI

Environment

Jupyter Notebook for EDA

PostgreSQL for structured business queries

Power BI for dashboard creation

🔍 Exploratory Data Analysis (Python)

Performed inside Jupyter Notebook:

✔ Data Cleaning

Loaded dataset with pandas

Used .info() and .describe() for structure & summary

Imputed missing review ratings using median per product category

Renamed columns into snake_case for readability

✔ Feature Engineering

Created age_group using binned age ranges

Derived purchase_frequency_days

Dropped redundant promo_code_used column after consistency check

✔ Database Integration

Connected Python to PostgreSQL

Loaded cleaned DataFrame into database for SQL analysis

🧮 SQL Business Analysis (PostgreSQL)

Key questions answered using SQL:

Revenue by gender

High-spending customers who used discounts

Top 5 products by average rating

Standard vs Express shipping comparison

Subscribers vs non-subscribers: revenue & average spend

Most discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top 3 best-selling products per category

Relationship between repeat purchases and subscriptions

Revenue contribution by each age group

📊 Power BI Dashboard

The dashboard includes:

Revenue and average spend KPIs

Category and product performance

Customer segmentation visuals

Discount usage patterns

Shipping type comparison

Demographic insights (age, gender, subscription)

Rating and review analysis

This allows stakeholders to explore insights interactively.

⭐ Key Insights

Subscribers tend to spend more on average than non-subscribers

Certain products show strong discount dependency

Express shipping users contribute higher revenue

Specific age groups show strong purchasing power

Loyal customers (high purchase frequency) provide consistent revenue

💡 Business Recommendations

Promote subscription benefits to increase conversions

Launch loyalty programs targeting frequent buyers

Optimize discount strategy to reduce margin loss

Highlight top-rated and best-selling products in campaigns

Target marketing to high-value demographics

Personalize recommendations for repeat buyers

🧠 What I Learned

End-to-end data analytics workflow

Real SQL-based business problem-solving

Feature engineering & data preprocessing

Power BI dashboard development

Translating data into actionable insights

👤 Author

Devvrat Tiwari
Data Analytics Student
📧 Email: devvrattiwari2005@gmail.com