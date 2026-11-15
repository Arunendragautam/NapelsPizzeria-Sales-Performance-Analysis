# 🍕 Napels Pizzeria Sales Data Analysis Project

![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![SQL](https://img.shields.io/badge/Language-SQL-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Introduction

This project analyzes **Napels Pizzeria** sales data using **MySQL** to extract meaningful insights and trends. The dataset is sourced from Kaggle and contains information about pizza sales, order quantities, pizza types, sizes, prices and order timestamps. The goal is to answer several business-related questions by writing SQL queries.

---

## Objectives

### Basic Queries
1. **Total Number of Orders Placed:** Query the total number of orders from the dataset.
2. **Total Revenue from Pizza Sales:** Calculate the total sales by summing up all pizza prices across orders.
3. **Highest Priced Pizza:** Find the pizza with the maximum price.
4. **Most Common Pizza Size Ordered:** Identify the most frequently ordered pizza size.
5. **Top 5 Most Ordered Pizza Types:** List the top 5 pizza types by quantity ordered.

### Intermediate Queries
1. **Total Quantity of Each Pizza Category Ordered:** Use SQL `JOIN` to merge tables and retrieve category-wise order quantities.
2. **Distribution of Orders by Hour:** Analyze how orders are distributed across different times of the day.
3. **Category-wise Pizza Distribution:** Group and join tables to see how pizzas are distributed across categories.
4. **Average Number of Pizzas Ordered per Day:** Group orders by date and calculate the daily average.
5. **Top 3 Most Ordered Pizza Types by Revenue:** Find the top 3 pizza types that generated the most revenue.

### Advanced Queries
1. **Percentage Contribution of Each Pizza Type to Total Revenue:** Calculate each pizza type's share of total revenue.
2. **Cumulative Revenue Over Time:** Analyze how revenue grows over time.
3. **Top 3 Most Ordered Pizza Types by Revenue for Each Category:** Find the top 3 pizza types within each category based on revenue.

---

## Dataset

**Source:** Pizza Sales Dataset on Kaggle

The dataset includes details on:
- Order IDs
- Pizza types and sizes
- Prices
- Timestamps of orders

---

## Project Structure

| File | Description |
|---|---|
| `NapelsPizzeria_Data.csv` | The raw sales data used in this project |
| `pizza_sales.sql` | SQL scripts with the queries for the questions above |
| `README.md` | Project documentation |

---

## Load the Dataset

To load the Napels Pizzeria sales data into MySQL Workbench:

1. **Open MySQL Workbench** and launch the application.
2. **Navigate to Data Import:** Go to the `Server` menu and select `Data Import`.
3. **Select the CSV file:** Browse and select `NapelsPizzeria_Data.csv` from your computer.
4. **Import the data:** Map the CSV columns to the fields in the new table, click `Next` and complete the import.

The CSV data will be loaded into a new table in MySQL.

---

## Run SQL Queries

1. Open the `pizza_sales.sql` file in MySQL Workbench.
2. Execute the queries to retrieve the insights for each project question.

---

## View Results

After running the queries, view the output of each one directly in MySQL Workbench. The results answer questions such as:
- Total number of orders placed
- Total revenue generated from pizza sales
- Most ordered pizza types, and more

---

## Results and Analysis

1. **Total Orders Placed:** The dataset contains **X** total orders.
2. **Total Revenue Generated:** The total revenue from pizza sales is **$Y**.
3. **Highest Priced Pizza:** The highest priced pizza is the **Z Pizza**, priced at **$A**.
4. **Most Common Pizza Size Ordered:** The most commonly ordered size is **B**.
5. **Top 5 Most Ordered Pizza Types:**
   - Pizza 1 - Qty: Q1
   - Pizza 2 - Qty: Q2
   - Pizza 3 - Qty: Q3
   - Pizza 4 - Qty: Q4
   - Pizza 5 - Qty: Q5

> **Note:** Replace the placeholder values above (X, Y, Z, A, B, Q1 to Q5) with the actual results from your queries.

---

## Future Work

- **Predictive Model:** Build a model using the data to forecast future pizza sales.
- **Customer Segmentation and Promotions:** Perform deeper analyses such as customer segmentation and the success rate of different promotions.

---

## Conclusion

This analysis offers valuable insights into Napels Pizzeria's sales patterns, popular pizza types and revenue-generating products. By using MySQL to query and analyze the dataset, we extracted actionable information that can drive future business decisions and enhance customer engagement strategies.

---

## Author

**Arunendra Gautam**
- 📫 Email: [arunendragautam9@gmail.com](mailto:arunendragautam9@gmail.com)
- 🌐 LinkedIn: [Arunendra Gautam](https://www.linkedin.com/in/arunendra-gautam-a22069208/)
- 💻 GitHub: [Arunendragautam](https://github.com/Arunendragautam)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

© 2026 Arunendra Gautam. All rights reserved.
