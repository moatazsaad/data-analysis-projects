# Sales Analysis & Dashboard Project 

## Project Overview
This project analyzes 2004 sales data to answer stakeholder questions about product performance, customer behavior, profitability, and credit limits. Insights are presented through an interactive Power BI dashboard.

## Objective
- Analyze sales breakdowns by product and country.
- Evaluate product pairings and customer purchase patterns.
- Assess profitability and net profit trends.
- Visualize insights in Power BI.

## Steps Taken

### 1. Data Extraction and Preparation (MySQL)
- Joined multiple tables: `orders`, `order_details`, `products`, `customers`, `employees`, and `offices`.
- Selected key columns: order info, product details, quantities, prices, customer and office locations.
- Created calculated columns in SQL:
  - **Sales Value** = `Quantity Ordered * Price Each`
  - **Cost of Sales** = `Quantity Ordered * Buy Price`
- Saved the query as a **view** (`SalesData for Power BI`) for easy connection to Power BI.

### 2. Power BI Dashboard Setup
- Connected Power BI to the MySQL view.
- Formatted the canvas with a dark theme and custom size.
- Added layout shapes for navigation, chart areas, and menus.
- Prepared placeholders for charts to visualize sales, net profit, and product/country insights.

### 3. Excel Analysis (Supplementary Calculations)
- Calculated **Net Profit** = Sales Value – Cost of Sales.
- Created pivot tables and charts to summarize:
  - Sales by product and country
  - Cost of sales and net profit
- Analyzed product purchase patterns using CTEs and self-joins to find frequently bought-together items.
- Evaluated customer behavior by credit limits:
  - Grouped customers into credit ranges
  - Calculated total sales, order count, and average sales per order
- Tracked purchase behavior over time using SQL `ROW_NUMBER()` and `LAG()`, exported to Excel for pivot summaries.

## Outcome
- Detailed insights into 2004 sales, including:
  - Product performance and profitability
  - Country-level contributions
  - Product pairings
  - Customer behavior by credit limit
  - Purchase value trends over time
- Fully prepared dataset for interactive visualization in Power BI.

## Tools & Technologies
- **Databases:** MySQL
- **Data Analysis:** SQL, Excel
- **Visualization:** Power BI
