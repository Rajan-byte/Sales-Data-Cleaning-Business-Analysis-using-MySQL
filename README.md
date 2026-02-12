📊 Sales Data Cleaning & Business Analysis using MySQL

🔹 Project Overview
This project simulates a real-world messy sales dataset (800+ rows) and demonstrates end-to-end data cleaning and business analysis using MySQL.
The dataset intentionally included:
1. Missing values
2. Invalid dates
3. Inconsistent country names
4. Negative and null prices
5. Duplicate / inconsistent gender formats
6. Text in numeric columns
7. Invalid quantities

The goal was to transform raw, dirty data into a structured dataset and extract meaningful business insights.

🛠 Tools Used: 
1. MySQL Workbench
2. SQL
3. CSV (raw data handling)

🧹 Data Cleaning Process: 

1️⃣ Created Raw Table
Imported CSV into MySQL as VARCHAR fields.

2️⃣ Created Cleaned Table
Used a separate cleaned table to preserve raw data.

3️⃣ Data Standardization
1. Standardized gender values (M, male → Male)
2. Standardized country names (US, United States → USA)
3. Converted product names to uppercase
4. Removed invalid ages (negative, unknown)
5. Removed negative and NULL prices
6. Removed zero and negative quantities
7. Converted string dates into proper DATE format
8. Created numeric columns for price, quantity, and age

📊 Business Questions Answered:

1. Highest revenue-generating product
2. Average order value
3. Country with most orders
4. Most used payment method
5. Repeating customers (more than 3 orders)
6. Monthly sales trend
7. Highest spending age group

📈 Key SQL Concepts Used

1. GROUP BY
2. HAVING
3. CASE statements
4. Subqueries
5. Date formatting
6. Aggregate functions (SUM, AVG, COUNT)

💼 Business Impact

1. This project demonstrates:
2. Real-world data cleaning skills
3. Data transformation best practices
4. Business-driven analysis
5. Analytical thinking
6. Structured SQL querying
7. Data preparation for dashboard visualization (Power BI)

🚀 Next Step
#This cleaned dataset will be used to build an interactive Power BI dashboard with KPI tracking and business insights visualization.
