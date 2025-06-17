# 📘 SQL Mock Test for Advanced Level – Main Branch

## 👨‍💻 Assignment Title: SQL Mock Test for Advanced Level  
**Case Study:** Advanced SQL for Food Delivery Service – *QuickBites*

---

## 📄 Overview

This project simulates a real-world case study for a food delivery service called **QuickBites**. The database tracks customers, restaurants, dishes, orders, delivery personnel, and reviews. The assignment emphasizes advanced SQL concepts such as window functions, complex joins, and analytical queries to extract business insights and analyze customer behavior.

---

## 🏗️ Database Design

The database consists of the following six core tables:

1. **Customers** – Tracks user details.
2. **Restaurants** – Information about partner restaurants.
3. **Dishes** – Menu items available at restaurants.
4. **Orders** – Tracks customer orders, linked to restaurants and dishes.
5. **Deliveries** – Details about the delivery personnel handling the orders.
6. **Reviews** – Ratings and feedback from customers.

The SQL file includes:
- `CREATE TABLE` statements with foreign key constraints
- `INSERT INTO` statements to populate each table with sample records
- `SQL Queries` to solve advanced business questions

---

## 🧪 SQL Tasks Covered

The SQL script covers **20 queries**, categorized as:

### 🔹 Basic Queries
- List all dishes with restaurant names and prices
- Average rating of restaurants in a city

### 🔹 Intermediate Queries
- Total revenue by restaurant
- Customers with multiple orders

### 🔹 Advanced Queries with Window Functions
- Rank restaurants by average customer ratings
- Cumulative total revenue per restaurant
- Top 2 most ordered dishes in each city
- Average delivery time per delivery person and ranking

### 🔹 Aggregations and Grouping
- Order count per city
- Average order value by cuisine

### 🔹 Filtering
- Reviews with rating below 4
- Orders placed after a specific date

### 🔹 Joins
- Order details with restaurant and customer names
- Dishes ordered by each customer

### 🔹 Subqueries
- Customer who gave the lowest rating
- Most expensive dish per cuisine

### 🔹 Analytical Queries
- Delivery person with fastest average delivery time
- Average delivery time for a specific delivery person
- Rank reviews by date per customer

### 🔹 Advanced Window Functions
- Running total of revenue for orders by each customer

---

## ✅ Output

All queries have been tested and return correct and meaningful results using the structured sample dataset.

---

## 📁 Branch Information

- **Main Branch:** Contains project overview.
- **Development Branch:** Includes schema setup, sample data, all query implementations, and deeper reflections on advanced SQL concepts.

---