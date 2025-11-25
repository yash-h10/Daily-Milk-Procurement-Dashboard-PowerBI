# Daily-Milk-Procurement-Dashboard-PowerBI
A multi-page Power BI dashboard designed to monitor daily milk procurement KPIs across multiple collection centers. Includes KPI cards, DAX measures, MCC-wise analysis, route categories, drill-through pages, and performance insights. Built using sample/manipulated data for learning and portfolio demonstration.

📊 Daily Milk Procurement & Operations Dashboard (Power BI)

Inspired by a real industry use case, recreated using sample/manipulated data for portfolio demonstration.

🧠 Project Overview

This Power BI report provides a comprehensive daily view of milk procurement operations across multiple Milk Collection Centers (MCCs).
It tracks procurement quantity, target achievement, transport cost efficiency, MPP performance, and route-wise distribution.

The dashboard is designed to help operational managers quickly identify issues, compare MCC performance, and take action using detailed drill-through analysis.

🎯 Key Objectives

Monitor daily procurement quantity vs target.

Track transport cost efficiency (TC) across MCCs.

Evaluate MPP (Milk Pouring Point) performance.

Highlight low-performing areas (e.g., Below 50 Litres, Less than 15 Pourers).

Provide actionable insights via drill-through pages.

Enable MCC-wise operational tracking through clean, interactive navigation.

🧩 Business Definitions
✔ TC (Transport Cost)

TC = Total Transport Expense / Milk Quantity
Used as a cost-efficiency indicator across MCCs.

✔ MPP (Milk Pouring Point)

The point/source where milk is poured/collected into the system.

✔ MCC (Milk Collection Center)

A location where milk from multiple MPPs is collected and weighed.

✔ Target Qty

Overall daily procurement target set for the entire operation (e.g., 125,000 litres).
Each MCC has its own internal target for performance tracking.

📌 Dashboard Pages & Features
### 🏠 1. Home Page (Overall Summary)

Includes:

Total Qty vs Target

Pouring MPP Gauge (Trend)

Today’s TC vs Yesterday (Efficiency Comparison)

MCC-wise Procurement Bar Chart

Route Category Classification (e.g., Local, Long Route, etc.)

MPP Category Distribution (Below 50, 50–100, >200, etc.)

Provides a quick health-check of the day’s operations.

🏢 2. MCC-Wise Pages (MCC 1 to MCC 5)

Each MCC has a dedicated analysis page that includes:

New MPP Count (Today)

Absent MPP Count

Total MPP < 50 Liters

Total MPP < 15 Pourers

Route-wise Transport Cost (TC)

Top 5 Procurement MPPs

Daily Qty Trend (Current Day vs Yesterday)

Custom KPIs & DAX measures

These pages allow MCC managers to quickly assess daily performance and problem areas.

🔍 3. Drill-Through Pages

Two specialized pages for issue analysis:

📉 Below 50 Litres MPP

Full list of all MPPs collecting under 50 litres

Bottom 20 MPPs by quantity (visualized)

Used for identifying locations with supply drop issues

🔻 Less Than 15 Pourers

All MPPs with <15 pourers (suppliers)

Bottom 10 MPPs based on pourers

Helps locate supply chain bottlenecks

🛠 Tools & Techniques Used

Power BI Desktop

DAX Functions (CALCULATE, SUMX, FILTER, DIVIDE, etc.)

Power Query (ETL) — data cleaning & transformation

Data Modelling (relationships, star-schema style)

Interactive Drill-Through Navigation

Advanced Visual Formatting

📂 Repository Contents

Daily_Operations_Dashboard.pbix — Power BI file

Dashboard_Screenshots.pdf — Multi-page visual overview

README.md — Project documentation

🔐 Data Disclaimer

This dashboard uses manipulated/sample data for portfolio purposes.
No real company data has been used or shared.

🌐 Future Enhancements

Add time-series comparison across weeks/months

Integrate forecasting (ARIMA / Prophet)

Add automated refresh using Power Automate

Build a mobile-friendly version

👤 Connect With Me

If you’d like to discuss this dashboard or offer feedback, feel free to connect on LinkedIn.
