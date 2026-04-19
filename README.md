# ecommerce-sales-sql-analysis
SQL project analyzing e-commerce sales data to uncover revenue trends, customer behavior, and product performance.

## Project Overview
This project analyzes an e-commerce sales dataset using SQL to uncover key business insights such as revenue trends, customer behavior, product performance, and geographic sales distribution.

The goal of this project is to demonstrate SQL skills used in real-world business analysis, including data exploration, aggregation, ranking, and trend analysis.

## Tools Used
- SQL (MySQL)
- GitHub
- Excel (for dataset preparation)

## Dataset Description
The dataset contains transaction-level e-commerce order data with the following fields:

| Column | Description |
|------|-------------|
| order_id | Unique identifier for each order |
| user_id | Unique identifier for each customer |
| product_id | Unique identifier for each product |
| category | Product category |
| price | Price per unit |
| qty | Quantity purchased |
| total_price | Total price of the order |
| order_date | Date and time of the transaction |
| country | Country where the order was placed |
| customer_segment | Customer segment classification |


## Analysis Performed

### 1. Data Exploration
- Total records
- Unique countries
- Customer segments

### 2. Revenue Analysis
- Total revenue
- Revenue by country
- Revenue by product category

### 3. Customer Analysis
- Top customers by revenue
- Revenue ranking using SQL window functions
- Customer segment performance

### 4. Product Analysis
- Top 10 products by revenue

### 5. Time-Based Analysis
- Monthly revenue trends

## Key Insights
- Identified highest revenue generating countries
- Determined most profitable product categories
- Found top spending customers
- Observed monthly revenue patterns

## How to Run This Project
1. Create the database
2. Import the dataset
3. Run the SQL queries in `ecommerce_analysis.sql`

## Meg
SQL Portfolio Project
