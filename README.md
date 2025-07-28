# 🧹 Data Cleaning Steps in Excel

To ensure clean and reliable data before analysis, I followed these data cleaning steps:

- 🗑️ Remove Unwanted Columns  
- 🔍 Detect and Correct Data Types  
- ❗ Handle Missing Values  
- ✂️ Remove Extra Spaces / Fix Wrong Formats  
- 🚫 Remove Null Entries  
- 🔄 Fix Inconsistent Text Entries (e.g., "Male", "M", "MALE")  
- 📋 Remove Duplicates  
- ⚠️ Correct Wrong Data Types (e.g., text instead of numbers)

**🛠️ Tools & Techniques Used:**
- `TRIM`, `IF`, and other Excel formulas  
- Remove Duplicates, Flash Fill, Text-to-Columns  
- Converted text to proper case and data types

**✅ Outcome:**  
Cleaned credit card transaction data, ready for seamless import into Power BI for dashboard creation.

---

# 🍕 SQL-Based Pizza Sales Analysis

## 📊 Introduction  
I performed a detailed analysis of pizza sales using SQL by cleaning, joining, and aggregating relevant tables to derive key business insights.

## ❓ Key Questions Answered

1. 📦 Retrieve the total number of orders placed  
2. 💰 Calculate the total revenue generated from pizza sales  
3. 🔝 Identify the highest-priced pizza  
4. 🍕 Find the most common pizza size ordered  
5. 🏆 List the top 5 most ordered pizza types along with their quantities  
6. 📊 Join necessary tables to find total quantity of each pizza category ordered  
7. ⏰ Analyze order distribution by hour of the day  
8. 📂 Find category-wise pizza distribution using joins  
9. 📅 Group orders by date to calculate average number of pizzas ordered per day  
10. 💸 Identify top 3 most ordered pizza types based on revenue

**🧠 Tools Used:**  
- SQL JOINS (INNER, LEFT)  
- GROUP BY, ORDER BY  
- Aggregate functions: `SUM`, `COUNT`, `MAX`, `AVG`

---

# 👥 HR Dashboard – Power BI

## 📌 Project Overview  
Created a comprehensive HR Dashboard using Power BI, focusing on key HR metrics and interactive visuals for easy analysis.

## 🎯 KPIs Tracked

- 👤 Total Headcount  
- 📉 Attrition Rate  
- ⏳ Average Tenure  
- 🚻 Gender Diversity

## 🧰 Tools & Techniques

- Connected data from Excel and SQL  
- Created DAX Measures for attrition and tenure  
- Used bar charts, cards, and slicers for interactivity  
- Enabled drill-down by department and location  
- Applied Row-Level Security (RLS) for data confidentiality  
- Published to Power BI Service with access restrictions

---

# 💼 Sales Dashboard – Power BI

## 📋 Project Summary  
Built an interactive Sales Dashboard in Power BI to track business performance and empower decision-making.

## 📊 KPIs Visualized

- 💵 Total Revenue  
- 📈 YoY Growth  
- 🛍️ Top-Selling Products

## 🧱 Data Model

- ⭐ Star Schema  
  - Fact Table: Sales  
  - Dimension Tables: Products, Customers, Date

## 🛠️ Techniques Used

- Created DAX Measures for sales growth and target achievement  
- Enabled filters by region, time, and sales rep  
- Implemented Row-Level Security (RLS) to restrict data access  
- Scheduled data refresh and published to Power BI Service

---

**✅ Result:**  
A fully dynamic, interactive, and secure dashboard that delivers actionable insights for HR and Sales leadership.
