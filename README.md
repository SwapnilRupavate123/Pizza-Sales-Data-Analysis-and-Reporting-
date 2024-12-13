
# Pizza Sales Data Analysis and Reporting

## Project Overview

This project involves analyzing pizza sales data to derive actionable insights, such as revenue trends, top-selling items, and order patterns. The analysis is performed using SQL queries to extract data from a relational database designed to manage pizza sales, orders, and product details. The goal is to support data-driven decision-making by identifying key business metrics, optimizing performance, and forecasting future trends.

## Features

- **Database Design**: Implemented a relational database schema to manage sales, orders, and pizza product data.
- **Revenue Analysis**: Calculated total revenue, identified top-selling pizzas, and analyzed sales by region and customer segment.
- **Data Insights**: Performed advanced data analysis using SQL JOINs, window functions, and aggregation techniques.
- **Performance Optimization**: Enhanced database performance using indexing and constraints to improve query efficiency.

## Project Structure

```plaintext
PizzaSales/
│
├── schema.sql             # SQL schema to create tables for pizza sales data
├── queries.sql            # SQL queries for revenue calculation and insights
├── readme.md              # Project overview and documentation
└── forecast.sql           # SQL script for 15-day sales forecasting
```

## Setup Instructions

### Prerequisites

- SQL Database (e.g., MySQL, PostgreSQL)
- SQL Client or IDE (e.g., DBeaver, MySQL Workbench)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/pizza-sales-analysis.git
cd pizza-sales-analysis
```

### 2. Create the Database
Run the `schema.sql` file to create the necessary tables for storing pizza sales data:
```sql
source schema.sql;
```

### 3. Populate the Database
Insert sample or actual pizza sales data into the tables using the provided `queries.sql` or through manual input.

### 4. Run Analysis Queries
Execute the queries in `queries.sql` to calculate:
- Total revenue generated
- Identify top-selling pizzas
- Analyze order trends
- Identify the most common pizza sizes and categories
- Generate forecasts based on sales data

## Key SQL Queries

- **Total Revenue**: Calculates the total revenue generated from pizza sales.
- **Top-Selling Pizzas**: Identifies the top 5 most ordered pizza types based on quantity.
- **Sales Trends**: Analyzes order trends by hour of the day and by customer segments.
- **Forecasting**: Creates a 15-day sales forecast to predict future revenue trends.

## Performance Improvements

- **Indexing**: Added indexes on frequently queried columns (e.g., `order_id`, `pizza_id`) to speed up query execution.
- **Data Integrity**: Enforced foreign key constraints to maintain data integrity across tables.

## Conclusion

This project offers a comprehensive solution for analyzing pizza sales data, enabling businesses to identify sales patterns, optimize inventory, and make data-driven decisions.
