# Electric-Vehicle-EV-Sales-Analysis-in-India
This project analyzes Electric Vehicle (EV) sales across Indian states, vehicle categories, and manufacturers to understand adoption trends, compare EV penetration, evaluate manufacturer performance, and generate business insights.
# 📌 Project Overview

This project analyzes Electric Vehicle (EV) sales across Indian states, vehicle categories, and manufacturers to understand adoption trends, compare EV penetration, evaluate manufacturer performance, and generate business insights.

The workflow follows a real analytics pipeline: raw data → SQL data cleaning → Python EDA → Power BI interactive dashboard.

# 🎯 Business Problem

## The EV market in India is growing rapidly due to government initiatives and rising environmental awareness. Businesses and policymakers need clear insight into:

Which states are leading (or lagging) in EV adoption
Which manufacturers dominate the market
How 2-Wheeler vs 4-Wheeler adoption compares
What the EV penetration rate looks like over time and geography

This project turns raw sales data into insights that support strategic decisions around marketing, production, and infrastructure investment.

# 🎯 Business Objectives
Analyze EV sales trends across India
Compare state-wise EV performance
Study manufacturer (maker) performance
Analyze vehicle category distribution (2-Wheeler vs 4-Wheeler)
Measure EV penetration rate
Generate actionable business recommendations
Build an interactive Power BI dashboard for stakeholders

# 🗂️ Dataset Description

## Three datasets were used:

### Dataset	Description	Key Columns
| Dataset | Description | Key Columns |
|---------|-------------|-------------|
| electric_vehicle_sales_by_state | State-wise EV sales, total vehicle sales, and category | date, state, vehicle_category, electric_vehicles_sold, total_vehicles_sold |
| electric_vehicle_sales_by_makers | Manufacturer-wise EV sales | date, maker, vehicle_category, electric_vehicles_sold |
| dim_date | Date hierarchy for time-based analysis | date, fiscal_year, quarter, month, month_name |

Data period: April 2021 – March 2024 (fiscal years 2022–2024) Rows: 2,445 (state-level) · 816 (maker-level) · 36 (date dimension)

# 🛠️ Tools & Technologies
Stage	Tool
Data storage & cleaning	SQL (MySQL)
Exploratory Data Analysis	Python (Pandas, NumPy, Matplotlib, Seaborn)
Notebook environment	Jupyter Notebook
Dashboard & visualization	Power BI
Version control	Git & GitHub









