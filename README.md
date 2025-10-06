# 🛍️ Myntra Sales Analysis Dashboard
<img width="2750" height="1540" alt="image" src="https://github.com/user-attachments/assets/b024ee66-d8ca-43dd-9cba-56e3e193c219" />

### Project Overview
This repository contains the interactive Power BI dashboard for Myntra Sales Analysis. The objective of this project is to transform raw sales and order data into actionable business intelligence, providing a clear, comprehensive, and interactive view of Myntra's performance across key dimensions.

The dashboard empowers stakeholders to:

1. Track overall sales health and key financial metrics.

2. Analyze sales performance across different time periods (monthly, yearly).

3. Identify top-performing brands and categories.

4. Uncover geographical sales distribution patterns.

5. Key Insight Focus: Performance measurement, trend identification, and segmentation by product and geography.

### 📊 Dashboard Key Metrics and Features
The dashboard is structured into several sections, focusing on key performance indicators (KPIs) and detailed distributions.

#### 1. Key Performance Indicators (KPIs)
The top section provides an immediate snapshot of overall performance:
1. Total Orders: The aggregate count of all transactions.
2. Total Revenue: The total sales amount generated.
3. Avg Sales Amount: The average value per order.
4. Total Discount & Avg Discount: Metrics to evaluate promotional effectiveness.
5. Product Count: The total number of unique products sold.

#### 2. Time-Series and Distribution Analysis
1. Total Sales Amount by Discount (Monthly Trend): Tracks monthly revenue performance and overlays the average discount offered, allowing for correlation analysis between promotions and sales volume.
2. Total Sales Distributed by Day/Category: Shows weekly sales trends segmented by primary product category (e.g., Men, Women, Kids, Beauty) to identify peak selling days.
3. Total Sales of Category (Year-by-Year Stacked): Provides a visual comparison of sales performance across different categories (e.g., Q1, Q2) over multiple years, enabling year-over-year growth comparison.

#### 3. Segmentation & Geographical Analysis
1. Product by Category: Doughnut/Pie chart illustrating the percentage distribution of sales revenue across major product categories.
2. Product / Brand Distribution: Bar charts highlighting the Top N performing brands and product sub-categories based on total revenue.
3. Total Revenue by State: A choropleth map or bar chart visualization showing sales contribution from different states or regions, crucial for logistics and marketing focus.

#### 4. Interactive Filters
The dashboard features extensive filters to drill down into specific contexts:
1. Year Filter: Allows comparison of performance for 2021, 2022, and 2023.
2. Category, Brand Name, and Sub-category Slicers: Enable focused analysis on specific market segments.

### 🛠️ Tools and Technologies
1. Primary Tool: Microsoft Power BI Desktop
2. Power Query Editor for initial data extraction, cleaning, and transformation (e.g., date hierarchy creation, column renaming).
3. Analysis: Data Analysis Expressions (DAX) for complex calculations, time-intelligence functions (e.g., YOY growth), and creating dynamic measures.

### 🚀 Getting Started
To explore this interactive dashboard locally:
1. Clone the Repository: Download or clone the contents of this repository to your local machine.
2. Install Power BI Desktop: Ensure you have the latest version of Microsoft Power BI Desktop installed.
3. Open the File: Locate and open the .pbix file
4. Interact: The dashboard will load with default settings. Use the slicers on the left pane and the year filters to drill down into specific sales performance periods and segments.
