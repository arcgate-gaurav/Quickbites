# SQL Mock Test for Advanced – Development Branch

## ✨ Reflection & Learning Summary

This branch captures my advanced SQL learning and practical understanding through the QuickBites Food Delivery case study. It simulates real-world data analysis for a food delivery service using complex joins, window functions, and aggregations.

---

## What I Understood

### 1. **Schema Design & Business Context**
- Modeled a real-world delivery platform with interconnected entities like customers, orders, dishes, and delivery personnel.
- Designed tables with foreign keys to enforce data relationships and maintain integrity.

### 2. **Data Population Strategy**
- Inserted meaningful and realistic sample data.
- Understood the dependency flow between parent and child tables (e.g., Orders depend on Customers and Restaurants).

### 3. **Complex Querying & Analytics**
- Used aggregations, subqueries, and joins to analyze revenue, order trends, and customer engagement.
- Explored window functions for ranking and cumulative metrics.

### 4. **Insight Derivation**
- Created queries that reflect core business KPIs like top dishes, delivery performance, customer frequency, and cuisine-based sales.

---

## Key Learnings

| Area                  | What I Learned                                                                 |
|-----------------------|--------------------------------------------------------------------------------|
| **Window Functions**  | Ranking, running totals, and cumulative analysis across partitions              |
| **Advanced Aggregations** | Used `GROUP BY`, `HAVING`, and nested aggregations for insights           |
| **Joins & Relationships** | Combined multiple tables to analyze full-order lifecycle                  |
| **Analytical Thinking** | Extracted business insights like top performers, repeat customers, efficiency |
| **Subqueries**        | Identified highest/lowest rated entities using inner and correlated subqueries  |

---

## 🚀 Skills Gained

- ✅ Building normalized relational schemas for service-based domains
- ✅ Writing complex SQL queries with window functions and grouping logic
- ✅ Analyzing performance metrics (e.g., delivery speed, dish popularity)
- ✅ Creating KPIs using SQL logic: top dishes, revenue per cuisine, ranking reviews
- ✅ Using subqueries to identify extreme cases like lowest ratings or most expensive dishes

---

## 🧪 Sample Business Questions Answered

- 🔍 **Which dishes are the most ordered in each city?**
- 📦 **Who are the customers with repeat orders?**
- ⭐ **Which restaurants perform best based on customer reviews?**
- 🕒 **Who are the fastest delivery personnel?**
- 💰 **What’s the cumulative revenue trend per restaurant?**

---

## 📌 Conclusion

This advanced SQL case study significantly sharpened my skills in writing production-level queries and applying business logic using relational data. It bridged theoretical concepts with real-world analytics—crucial for roles in data analysis, BI, and backend systems.

By completing this, I’ve not only reinforced core SQL techniques but also expanded my ability to solve practical business problems using advanced SQL tools.