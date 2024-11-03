# 📊 Power BI Sales Insights Project

This project is an interactive Power BI dashboard that visualizes sales data across various dimensions, enabling users to gain actionable insights into revenue trends, customer behavior, and product performance. The dashboard integrates with an SQL database and utilizes ETL (Extract, Transform, Load) processes to ensure data accuracy and relevance. Power Query was used extensively for data transformation and cleaning.

### Dashboard Screenshot

![Dashboard Screenshot](Screenshot%202024-11-03%20172110.png)

## 🌟 Project Overview

The dashboard provides several interactive and analytical features, including:

### 🛠️ Interactive Dashboard Functionalities

- **💰 Revenue and Sales Quantity Overview**: At a glance, users can see total revenue and sales quantity, providing a quick assessment of business performance.
- **🌐 Revenue by Markets**: An interactive bar chart displays revenue by different markets. Users can filter and drill down into specific regions to see how each market contributes to overall revenue.
- **📦 Sales Quantity by Markets**: This chart shows the quantity of sales across markets, offering insight into regions with high product movement, regardless of revenue.
- **📈 Revenue Trends Over Time**: A dynamic line chart depicting revenue trends from 2017 to 2020. Users can filter by year or month to explore seasonal trends or analyze revenue changes over specific timeframes.
- **👥 Top 5 Customers by Revenue**: Highlights the highest revenue-generating customers, allowing users to identify valuable client relationships.
- **🏆 Top 5 Products by Revenue**: Shows the top-performing products by revenue, helping in understanding product demand and focus areas for marketing.

### 🛠️ Data Transformation & ETL

This project employs ETL processes to prepare data for analysis. Here’s how the data was processed:

1. **Extract**: Data was loaded from the SQL database, containing raw sales data, customer details, product information, and regional data.
   
2. **Transform**: Using Power Query, I performed data cleaning and transformation tasks to ensure data quality:
   - 🧹 **Data Cleaning**: Removed duplicate entries, handled null values, and standardized formats for dates and text fields.
   - 🔄 **Data Transformation**: Aggregated data by markets, customers, and product categories to make it compatible with the dashboard requirements.
   - ➕ **Calculated Fields**: Created new fields, such as total revenue and sales quantities for each customer and product, to simplify visualizations.
   
3. **Load**: The transformed data was loaded into Power BI, where it was structured and organized for seamless integration with the dashboard visuals.

## 🔍 Key Benefits of the Interactive Dashboard

- **User-Friendly Filters**: Easily switch between years and months to adjust the time range of the analysis, enabling more granular insights.
- **Dynamic Drill-Downs**: Each chart allows for interactive drill-downs by market, product, or customer, providing flexibility to explore specific segments.
- **Data Accuracy**: The ETL process and Power Query transformations ensure that only clean, reliable data is displayed, reducing the risk of decision-making based on erroneous information.

## 📥 Instructions for Use

1. **Download the Power BI Template**: Open the `Sales Insights.pbit` file in Power BI.
2. **Database Setup**: Use the provided SQL scripts to set up the database and import sample data.
3. **Connect to SQL Data Source**: Link the Power BI file to the SQL database.
4. **Refresh Data**: Refresh the dashboard to load the latest data and interact with the visuals.

This Power BI dashboard, powered by efficient ETL and data transformation practices, offers a comprehensive view of sales data, allowing users to gain insights and drive data-informed decisions.
