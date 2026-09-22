# 🛒 E-Commerce SQL Data Analysis Project

## 📌 Project Overview

This project is an **E-Commerce Data Analysis project built using MySQL**.  
The main objective is to analyze customer, product, order, sales, profit, payment, shipping, and sales-channel data using SQL.

The project demonstrates practical SQL skills that are commonly used in **Data Analyst and Business Intelligence** workflows.

> **Dataset Note:** This is a synthetically generated dataset created for educational and portfolio purposes. It does not contain real customer information.

---

## 📊 Dataset Overview

The project contains four related tables:

| Table | Records | Description |
|------|--------:|-------------|
| `customers` | 150 | Customer details including city, state and region |
| `products` | 60 | Product catalog with category and price |
| `orders` | 1,000 | Order-level sales, quantity, discount, profit and transaction details |
| `employees` | 12 | Employee-manager hierarchy for SELF JOIN analysis |

### 🔹 Orders Table

Important columns:

- `Order_ID`
- `Customer_ID`
- `Product_ID`
- `Order_Date`
- `Quantity`
- `Discount`
- `Unit_Price`
- `Sales`
- `Profit`
- `Payment_Mode`
- `Sales_Channel`
- `Ship_Mode`
- `Category`

### 🔹 Customers Table

- `Customer_ID`
- `Customer_Name`
- `City`
- `State`
- `Region`

### 🔹 Products Table

- `Product_ID`
- `Product_Name`
- `Category`
- `Price`

### 🔹 Employees Table

- `Employee_ID`
- `Employee_Name`
- `Manager_ID`
- `Department`

---

# 🧠 SQL Concepts Covered

This project covers a wide range of SQL concepts:

### Basic SQL
- `SELECT`
- `WHERE`
- `AND`
- `OR`
- `IN`
- `BETWEEN`
- `LIKE`
- `DISTINCT`

### Aggregation
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`

### Grouping & Filtering
- `GROUP BY`
- `HAVING`

### Sorting & Limiting
- `ORDER BY`
- `ASC`
- `DESC`
- `LIMIT`

### JOINs
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `CROSS JOIN`
- `SELF JOIN`

### Subqueries
- Scalar Subqueries
- Aggregate Subqueries
- Correlated Subqueries
- Nested Subqueries

### Other SQL Concepts
- `CASE WHEN`
- Business calculations
- Customer analysis
- Product analysis
- Sales analysis
- Profit analysis

---

# 📂 Project Structure

```text
ecommerce-sql-data-analysis/
│
├── README.md
├── 02_queries.sql
│
└── data/
    ├── customers.csv
    ├── products.csv
    ├── orders.csv
    └── employees.csv
