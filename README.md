# 🛍️ E-Commerce SQL Analysis

This project demonstrates real-world SQL skills by analyzing an e-commerce dataset using SQL Server. It showcases business insights through 15 polished SQL queries.

----

## 📦 Dataset

- `ecommerce_data.csv`  
  Contains 1000+ rows of online order data including:
  - Order date
  - Customer and product details
  - Sales and country info

----

## 🧠 Key Business Questions Answered

- What is the total revenue?
- Which are the best-selling products?
- Which countries generate the most revenue?
- What is the daily sales trend?

----

## 🛠️ Tools Used

- SQL Server Management Studio
- SQL
- Git & GitHub

----

## 📊 Example Queries

```sql
-- Total Revenue

SELECT 
    SUM(quantity * unit_price) AS total_revenue
FROM 
    ecommerce_data$;

----
