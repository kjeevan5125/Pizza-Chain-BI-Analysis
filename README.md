# Pizza Chain Sales & Business Intelligence Analysis

## Project Overview

This project focuses on analyzing pizza sales data using SQL to uncover business insights related to sales performance, revenue, product demand, and customer ordering patterns.

A relational database structure is used to organize pizza order data across multiple tables. SQL queries are then used to explore the data, identify sales trends, and answer key business questions.

## Business Objectives

The analysis aims to answer important business questions such as:

- How many orders were placed?
- What is the total revenue generated from pizza sales?
- Which pizza has the highest price?
- What is the most commonly ordered pizza size?
- Which pizza types are ordered most frequently?
- Which pizza categories generate the highest sales?
- What are the peak ordering hours?
- How does revenue change over time?
- Which pizza types contribute the most to total revenue?

## Dataset

The dataset contains pizza ordering information organized into relational tables such as:

- `orders`
- `order_details`
- `pizzas`
- `pizza_types`

The data contains information about orders, pizza products, categories, sizes, quantities, prices, and order dates/times.

## Analysis Performed

### Sales & Revenue Analysis

- Calculated total revenue generated from pizza sales.
- Analyzed revenue contribution across different pizza types.
- Identified the highest-revenue-generating pizza products.
- Analyzed cumulative revenue over time.

### Product Analysis

- Identified the most frequently ordered pizza types.
- Found the most common pizza sizes.
- Analyzed pizza sales across different categories.
- Identified the highest-priced pizza.

### Order & Customer Behavior Analysis

- Analyzed the total number of orders.
- Studied the distribution of orders by hour of the day.
- Identified peak ordering periods.
- Calculated the average number of pizzas ordered per day.

### Advanced SQL Analysis

- Calculated percentage contribution of each pizza type to total revenue.
- Used ranking techniques to identify top-performing pizza types.
- Analyzed the top 3 pizza types by revenue within each category.
- Calculated cumulative revenue using window functions.

## SQL Concepts Used

The project demonstrates practical use of:

- `SELECT`
- `WHERE`
- `JOIN`
- `GROUP BY`
- Aggregate Functions
- `ORDER BY`
- Subqueries
- Window Functions
- `RANK()`
- Date & Time Functions
- Data Aggregation

## Database Design

The project uses a relational database structure to connect order, product, and pizza-related information.

Key relationships are established between tables such as:

```text
orders
   |
   | order_id
   ↓
order_details
   |
   | pizza_id
   ↓
pizzas / pizza_types
```

This structure allows transactional order data to be combined with product information for detailed sales analysis.

## Tools & Technologies

- **SQL** – Data querying, analysis, aggregation, and business insights
- **MySQL** – Relational database management
- **Excel** – Exploratory analysis and supporting data analysis

## Project Structure

```text
Pizza-Chain-BI-Analysis/
│
├── Dataset/
│   └── Dataset files
│
├── SQL Commands/
│   ├── 1_Creating Table.sql
│   ├── Q1.sql
│   ├── Q2.sql
│   ├── Q3.sql
│   ├── ...
│   ├── Q13.sql
│   └── All Q combined.sql
│
├── Questions.txt
└── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/kjeevan5125/Pizza-Chain-BI-Analysis.git
```

### 2. Create the database

Run the following SQL file:

```text
SQL Commands/1_Creating Table.sql
```

This creates the required database tables.

### 3. Load the dataset

Import the provided dataset into the corresponding database tables.

### 4. Run the analysis queries

Execute the individual SQL files from the `SQL Commands` folder or run:

```text
All Q combined.sql
```

### 5. Analyze the results

Review the query outputs to identify sales trends, product performance, revenue contribution, and ordering patterns.

## Key Skills Demonstrated

- Relational Database Design
- SQL Data Analysis
- Data Cleaning & Organization
- Sales & Revenue Analysis
- Business Intelligence
- Customer Behavior Analysis
- Data Aggregation
- Exploratory Data Analysis
- Analytical Problem Solving

## Future Enhancements

- Build an interactive Power BI dashboard for sales and revenue analysis.
- Add additional business KPIs and visualizations.
- Perform deeper customer and product segmentation.
