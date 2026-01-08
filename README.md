# Sales-Analysis-Project-SQL-Python-SQLite-
End-to-end sales analysis using SQL, Python, and SQLite. Built an ETL pipeline from CSV to database, performed regional and category-level profitability analysis, identified loss-making products and discount thresholds, and generated business-driven insights with visualizations.

📊 Sales Analysis Project (SQL + Python)
📌 Overview

This project performs an end-to-end sales and profitability analysis using the Sample Superstore dataset. It combines SQL, Python, and SQLite to analyze sales performance, identify loss-making products, evaluate discount impact, and generate actionable business insights.

🛠️ Tools & Technologies

Database: SQLite3

Language: Python

Libraries: Pandas, Matplotlib

Query Language: SQL

📂 Project Structure
sales_analysis/
├── data/        # Raw dataset (CSV)
├── sql/         # SQL queries
├── python/      # Python scripts (ETL & analysis)
├── output/      # Charts and results
└── sales.db     # SQLite database

🔄 Data Pipeline (ETL)

Extract: Loaded CSV data using Pandas

Transform: Cleaned data and ensured correct data types

Load: Stored structured data into SQLite database

🧮 Analysis Performed
SQL Analysis

Total sales and profit

Sales by region

Top 5 states by sales

Loss-making categories and sub-categories

Python Analysis

Profit by category and sub-category

Impact of discounts on profitability

Sales vs profit relationship

Distribution of profit per order

📈 Visualizations

Profit by Category (Bar Chart)

Profit/Loss by Sub-Category

Top Loss-Making Sub-Categories (Horizontal Bar Chart)

Average Profit by Discount (Line Chart)

Sales vs Profit (Scatter Plot)

Profit Distribution (Histogram)

💡 Key Business Insights

High revenue does not always mean high profit

Furniture losses are driven by specific sub-categories

Discounts above 40% consistently lead to losses

Profitability can improve with targeted operational fixes

🎯 Key Learnings

Practical use of SQL for business analysis

ETL using Python and SQLite

Translating data into meaningful business insights

🚀 Future Improvements

Dashboard integration (Power BI / Tableau)

Automated ETL pipeline

Time-series sales analysis

Streamlit deployment
