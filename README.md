# 🚴 Denver Bike Share – Sales & Revenue Analysis

## 📌 Project Overview
Analyzed bike-sharing data for 2021 and 2022 to understand sales performance, revenue trends, profitability, and customer behavior using MySQL and Power BI.

## 🛠️ Tools Used
- MySQL Workbench
- Microsoft Power BI
- DAX
- CSV Datasets

## 🔍 Project Workflow
- Imported and combined 2021 and 2022 datasets using SQL `UNION ALL`.
- Used `LEFT JOIN` to integrate sales data with the cost table.
- Calculated revenue and profit using SQL queries.
- Connected the SQL query output to Power BI.
- Created DAX measures and an interactive dashboard with KPIs, charts, and a year slicer.

## 📊 Business Questions Answered
- How do revenue, profit, and riders change over time?
- Which hours and weekdays have the highest rider activity?
- Which season generates the highest revenue?
- What is the distribution of registered and casual riders?
- Which months show the strongest business performance?

## 💡 Key Insights
- Registered riders account for 81.81% of total riders.
- Casual riders account for 18.19% of total riders.
- Rider activity peaks around 5 PM and 6 PM.
- Season 3 generates the highest seasonal revenue.
- September records the highest monthly revenue in the selected 2022 view.

## 📁 Project Files
- `bike_share_yr_0.csv` – 2021 data
- `bike_share_yr_1.csv` – 2022 data
- `cost_table.csv` – Cost data
- `Bike Sales Query for Power BI.txt` – SQL query
- `dashboard.png` – Dashboard screenshot

## 🚀 Conclusion
This project demonstrates an end-to-end data analytics workflow using SQL for data integration and analysis and Power BI for interactive visualization and business insights.
