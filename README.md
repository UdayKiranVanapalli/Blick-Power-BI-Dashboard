# Blinkit Sales Performance Dashboard
## Dashboard Link: [Blinkit Sales Performance Dashboard](https://drive.google.com/file/d/1lZiZ8X2WLLesf_6BoXSapjNWpFZoHbU_/view?usp=drive_link)
## Problem Statement
This dashboard provides a clear and actionable view of Blinkit's key sales performance metrics, focusing on outlet types, product categories, and sales trends over time. Its purpose is to help stakeholders make informed decisions based on real-time sales data.

# Key Questions:
-Which outlets perform the best based on sales and customer ratings?
-How do sales vary between different product categories?
-What are the trends in sales growth from 2010 to 2020?
# Tools Used:
For creating this dashboard, the following tools were utilized:
Power BI Desktop:
To load, clean, and visualize the dataset, providing interactive visuals like bar charts, card visuals, and slicers.
Power Query:
For data cleaning and transformation, including filtering unnecessary data and ensuring a high level of data quality.
DAX (Data Analysis Expressions):
Used to create calculated measures for sales insights, such as total revenue, average sales per item, and outlet performance by sales.

# Power BI Service:
To publish the dashboard online, making it accessible to relevant stakeholders for real-time insights.

# Dataset
The dataset used for this dashboard was derived from Blinkit's internal sales records, containing detailed information on product categories, outlets, sales, and customer ratings.

# Steps Followed:
Data Loading
Loaded Blinkit's sales data into Power BI Desktop for detailed analysis.
Data Transformation
Cleaned and transformed the dataset using Power Query, including handling null values and filtering out irrelevant columns.
Visualisation Creation

# Key visuals created include:
Outlet Performance by Sales (Clustered Bar Chart)
Category-wise Sales (Stacked Bar Chart)
Sales Growth Over Time (Line Chart)
Calculating Insights
Created DAX measures to calculate total sales, average sales per item, and outlet performance metrics. Aggregated sales data by outlet size, category, and location.

# Dashboard Design
Applied Blinkit's branding and a professional theme to the dashboard. Used text boxes to provide context and explanation of key metrics. Separated visuals for easy navigation and better user experience.

# DAX Expressions Used:
Total Sales: Total Sales = SUM(Sales[Revenue])

Average Sales per Item: Average Sales = DIVIDE(SUM(Sales[Revenue]), SUM(Sales[Items Sold]))

Outlet Performance: Performance = CALCULATE(SUM(Sales[Revenue]), Sales[Outlet Type])

# Visualisations:
Outlet Performance by Sales
A clustered bar chart highlighting the performance of Blinkit outlets across small, medium, and large store formats, along with their sales revenue.

Category-wise Sales
A stacked bar chart showing the breakdown of sales across various product categories like fruits, vegetables, snack foods, and household items.

Sales Growth Over Time
A line chart representing Blinkit's sales performance across a decade (2010-2020), providing insights into growth trends.

# Key Insights:
1. Outlet Performance:
Large Outlets contribute to over 50% of total sales revenue.
Top Performers include grocery stores and hypermarkets.
2. Product Categories:
Fruits & Vegetables hold the highest sales volume, followed closely by Snack Foods.
Sales in Household Products have grown steadily, indicating increased consumer demand.
3. Sales Growth:
From 2010 to 2020, Blinkit's total sales grew by 25%, with noticeable peaks during festive seasons.
How to Access and Use the Dashboard
## Click on the dashboard link to view screen recording: [Blinkit Sales Performance Dashboard](https://drive.google.com/drive/folders/14MG4UQ5ZNaGr1i41mz2Gp4-h1qAda07h?usp=sharing)

Use interactive filters like outlet type, product category, and time period to explore various aspects of sales performance.
Hover over visuals to view additional details and in-depth insights into Blinkit's sales metrics.

Screenshots
![Overall Dashboard View](https://github.com/user-attachments/assets/ee39b42c-7c62-498d-a0df-b2ac10adeafd)
Overall Dashboard View   -   Outlet Performance Breakdown   -Category-wise Sales Insights
# Conclusion
The Blinkit Sales Performance Dashboard offers a detailed, real-time overview of the company's sales performance, enabling stakeholders to track outlet performance, analyze product category trends, and monitor long-term growth. It’s a valuable tool for data-driven decision-making, empowering Blinkit to optimize its sales strategy and improve customer satisfaction.

Author: Uday Kiran Vanapalli
October 2024
