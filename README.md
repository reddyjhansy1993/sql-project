# sql-project
# ✈️ SQL Capstone Project – Airline Database Analysis

## 📌 Project Overview
This SQL capstone project is based on the **Airline Database**, which contains data related to airline bookings, tickets, flights, airports, and transactions.  
The project focuses on writing optimized SQL queries to extract meaningful business insights.

All queries were validated and evaluated as part of a structured SQL assessment.

---

## 🗂 Database Used
**AirlineDB**

The database includes:
- Bookings
- Tickets
- Boarding passes
- Flights
- Airports
- Orders and transactions

---

## 🎯 Objectives
- Analyze airline operational data using SQL  
- Write complex queries using joins, aggregations, and window functions  
- Solve real-world business problem statements  
- Generate accurate, structured outputs  

---

## 🛠 SQL Concepts Used
- SELECT, WHERE, GROUP BY, ORDER BY  
- INNER JOIN, LEFT JOIN  
- Aggregate functions (COUNT, SUM)  
- Date functions  
- Window functions (RANK)  
- Subqueries & CTEs  

---

## 📊 Problem Statements Solved

### 🔹 1. Tickets Without Boarding Passes
**Task:**  
Identify how many tickets exist without boarding passes.

**Approach:**  
- Used LEFT JOIN between tickets and boarding_passes  
- Filtered NULL boarding pass records  

✅ **Result:** Correct output obtained (10/10 score)

---

### 🔹 2. Booking Date Formatting
**Task:**  
Represent booking dates in `YYYY-MM-DD` format.

**Approach:**  
- Used date formatting functions  
- Selected booking reference, formatted date, and total amount  

✅ **Result:** Correct output obtained (10/10 score)

---

### 🔹 3. Airport Ranking by Departing Flights
**Task:**  
Rank airports based on the number of departing flights.

**Approach:**  
- Counted flights per departure airport  
- Used `RANK()` window function  

✅ **Result:** Correct output obtained (10/10 score)

---

### 🔹 4. Most Popular Product per Store (Bike Sharing Dataset)
**Task:**  
Identify the most popular product in each store based on quantity sold.

**Approach:**  
- Aggregated product quantities  
- Grouped by store and product  

---

### 🔹 5. Quarterly Store Sales & Ranking
**Task:**  
Calculate total sales per store for each quarter and rank store performance.

**Approach:**  
- Extracted year and quarter  
- Calculated total sales using quantity × price × discount  
- Applied ranking using window functions  

---

## 📂 Files Included
- `airline_db_queries.sql` – All SQL queries used in the project  
- `screenshots/` – Query execution results and score validations  

---

## 📌 Key Learnings
- Writing structured and optimized SQL queries  
- Handling real-world datasets  
- Using window functions for ranking analysis  
- Applying SQL for business decision-making  

---

## ⭐ Evaluation
- **Score Achieved:** 10/10  
- **Status:** Successfully completed SQL Capstone  

---

## 📫 Contact
- LinkedIn: https://www.linkedin.com/in/reddy-jhansy-102119120  
- GitHub: https://github.com/reddyjhansy1993  

