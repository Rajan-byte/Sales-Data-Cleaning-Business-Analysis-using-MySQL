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
> Standardized gender values (M, male → Male)
> Standardized country names (US, United States → USA)
> Converted product names to uppercase
> Removed invalid ages (negative, unknown)
> Removed negative and NULL prices
> Removed zero and negative quantities
> Converted string dates into proper DATE format
> Created numeric columns for price, quantity, and age

📊 Business Questions Answered:

> Highest revenue-generating product
> Average order value
> Country with most orders
> Most used payment method
> Repeating customers (more than 3 orders)
> Monthly sales trend
> Highest spending age group

📈 Key SQL Concepts Used

> GROUP BY
> HAVING
> CASE statements
> Subqueries
> Date formatting
> Aggregate functions (SUM, AVG, COUNT)

💼 Business Impact

> This project demonstrates:
> Real-world data cleaning skills
> Data transformation best practices
> Business-driven analysis
> Analytical thinking
> Structured SQL querying
> Data preparation for dashboard visualization (Power BI)

🚀 Next Step
>> This cleaned dataset will be used to build an interactive Power BI dashboard with KPI tracking and business insights visualization.
