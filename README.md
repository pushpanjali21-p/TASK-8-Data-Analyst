# TASK-8-Data-Analyst
Project Overview

This project is part of the Data Analyst Internship – Task 8.

The objective of this task is to design a simple interactive sales dashboard that analyzes sales performance by:

📅 Month

🌍 Region

📦 Category

The dashboard was created using Power BI Desktop.

🛠 Tools Used

Microsoft Power BI Desktop

Superstore Sales Dataset (CSV file)

📁 Dataset Information

The dataset contains the following key columns:

Order Date

Region

Category

Sales

Profit

Customer Name

Segment

The dataset was imported and checked for correct data types before building the dashboard.

🔄 Data Preparation Steps

Imported CSV file into Power BI.

Verified data types (Order Date as Date, Sales & Profit as Decimal).

Created a new column for Month-Year using DAX:

MonthYear = FORMAT([order_date], "MMM YYYY")

Sorted Month-Year properly using Order Date.

📊 Dashboard Visuals Created

1️⃣ Line Chart – Sales Over Months
Shows monthly sales trend.

2️⃣ Bar Chart – Sales by Region
Displays total sales for each region.

3️⃣ Donut Chart – Sales by Category
Shows contribution of each product category.

4️⃣ Slicer – Region
Allows filtering the dashboard interactively.

5️⃣ KPI Card – Total Sales
Displays overall total sales.
