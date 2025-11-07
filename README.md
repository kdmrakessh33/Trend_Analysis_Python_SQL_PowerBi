🛍️ Customer Shopping Behaviour Analysis
🧩 Overview

This project explores customer purchasing behavior using both Python and SQL. The goal is to uncover actionable insights from transactional data — such as spending trends, discount usage, subscription impact, and customer segmentation — and visualize the results through a Power BI dashboard and final presentation report.

The project demonstrates an end-to-end data analytics workflow:

Data loading and cleaning using Python

Exploratory Data Analysis (EDA)

SQL-based business analysis in PostgreSQL

Power BI visualization

Report and presentation creation

📂 Dataset

Name: Customer Shopping Behaviour Dataset

Description: Contains customer transaction records, including purchase amount, discount usage, shipping type, subscription status, and product category.


🛠️ Tools & Technologies
Category	Tools Used
Data Processing	Python (Pandas, NumPy)
Database & Querying	PostgreSQL
Business Intelligence	Power BI
Reporting	PowerPoint, MS Word
IDE / Notebook	Jupyter Notebook
🔍 Project Steps
1. Data Loading (Python)

Imported the dataset using Pandas

Checked data structure, missing values, and column types

2. Exploratory Data Analysis (EDA)

Conducted univariate and bivariate analysis

Explored spending patterns by gender, age group, and category

Identified relationships between discount usage, shipping type, and purchase behavior

3. Data Cleaning

Handled missing and inconsistent values

Removed duplicates

Standardized categorical values

Created new columns (e.g., Age_Group, Customer_Segment) for deeper analysis

4. SQL Analysis (PostgreSQL)

Performed advanced analytical queries to derive insights, such as:

💰 Revenue comparison by gender

🏷️ Discount impact on spending

⭐ Top 5 products by review rating

🚚 Purchase comparison between shipping types

🧾 Average and total revenue by subscription status

🎯 Customer segmentation (New, Returning, Loyal)

📦 Top products per category

🔁 Repeat buyers and subscription correlation

👥 Revenue contribution by age group

All queries are documented in Customer_Behaviour_Analysis.sql
.

5. Power BI Dashboard

Connected cleaned data / SQL views to Power BI

Designed an interactive dashboard with key metrics and filters

Included visuals for:

Category-wise revenue

Sales by category

Subscription performance

6. Reporting & Presentation

Compiled major insights and visuals into a PowerPoint presentation

Summarized findings, key drivers, and business recommendations

📈 Key Insights

Female customers contributed slightly higher total revenue.

Subscribed customers spent more on average than non-subscribers.

Products with higher discounts saw greater purchase frequency but lower average spend.

Loyal customers (more than 10 previous purchases) accounted for a large share of total revenue.

Express shipping correlated with higher average purchase value.
