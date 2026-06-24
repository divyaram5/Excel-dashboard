Project Overview

The Sales Analysis Dashboard is an interactive Microsoft Excel dashboard designed to analyze sales performance, revenue trends, customer orders, and delivery metrics.

The dashboard provides business insights through dynamic charts, KPI cards, and slicers, enabling users to quickly identify trends and make data-driven decisions.

🎯 Objectives

The dashboard helps answer the following business questions:

What is the total revenue generated?
How many orders were placed?
Which products generate the highest revenue?
Which categories perform best?
Which cities contribute the most orders?
How does revenue change by month and hour?
Which occasions generate maximum sales?
What is the average order delivery time?
🛠️ Tools & Technologies Used
Tool	Purpose
Microsoft Excel	Dashboard Development
Power Query	Data Cleaning & Transformation
Pivot Tables	Data Aggregation
Pivot Charts	Data Visualization
Slicers & Timelines	Interactive Filtering
Excel Formulas	KPI Calculations
📂 Dataset Information

The dataset contains the following information:

Order ID
Product Name
Category
Revenue
Order Date
Delivery Date
City
Occasion
Quantity Ordered
📈 Dashboard Features
1. KPI Cards

The dashboard contains four key performance indicators.

Total Orders

Displays the total number of orders placed.

Formula Used

=COUNTA(Order_ID)
Total Revenue

Displays total sales revenue.

Formula Used

=SUM(Revenue)
Average Delivery Time

Displays the average number of days between order and delivery.

Formula Used

=AVERAGE(Delivery_Date-Order_Date)
Order Count

Shows total processed orders.

📊 Visualizations
1. Top 5 Products by Revenue

Chart Type: Clustered Column Chart

Purpose:
Shows the five highest revenue-generating products.

Business Insight:
Helps identify the best-selling products.

2. Revenue by Category

Chart Type: Column Chart

Purpose:
Displays revenue contribution from each product category.

Business Insight:
Identifies high-performing and low-performing categories.

3. Revenue by Hour

Chart Type: Line Chart

Purpose:
Shows revenue trends across different hours of the day.

Business Insight:
Identifies peak purchasing times.

4. Revenue by Month

Chart Type: Line Chart

Purpose:
Displays monthly revenue trends.

Business Insight:
Helps understand seasonality and sales patterns.

5. Top 10 Cities by Orders

Chart Type: Column Chart

Purpose:
Shows cities with the highest number of orders.

Business Insight:
Identifies key geographic markets.

6. Revenue by Occasion

Chart Type: Column Chart

Purpose:
Displays revenue generated during special occasions.

Occasions Included

All Occasions
Anniversary
Birthday
Diwali
Holi
Raksha Bandhan
Valentine's Day

Business Insight:
Helps understand seasonal demand and festival-based sales performance.

🎛️ Interactive Features
Occasion Slicer

Allows users to filter dashboard data based on:

Anniversary
Birthday
Diwali
Holi
Raksha Bandhan
Valentine's Day
Order Date Timeline

Allows users to:

Filter by Year
Filter by Month
Analyze specific time periods
Delivery Date Timeline

Allows users to:

Filter deliveries by month
Analyze delivery trends
⚙️ Dashboard Development Process
Step 1: Data Collection

Imported raw sales data into Excel.

Step 2: Data Cleaning

Performed:

Removed duplicates
Handled missing values
Standardized date formats
Corrected data types

Tools Used:

Power Query
Excel Functions
Step 3: Data Modeling

Created:

Pivot Tables
Calculated Fields
Relationships between datasets
Step 4: Dashboard Creation

Developed:

KPI Cards
Charts
Slicers
Timelines
Interactive Filters
📊 Key Business Insights
✅ Colors category generated the highest revenue.
✅ Certain products significantly outperform others.
✅ Festival occasions drive higher sales.
✅ Revenue fluctuates across months, indicating seasonality.
✅ Some cities contribute more orders than others.
✅ Customer activity peaks during specific hours.
