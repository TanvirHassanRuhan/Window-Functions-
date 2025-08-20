# Advanced SQL Analytics — Case Studies & Queries

This repository contains **advanced SQL queries** using a sample database `advanced_sql_db`.  
It demonstrates techniques for **running totals, moving averages, growth analysis, ranking, and segmentation** — useful in real-world analytics and business intelligence.

---

## 📂 Database & Tables
- **Orders**  
- **Order_Items**  
- **Products**  
- **Categories**  
- **Customers**  
- **Regions**  
- **Sales_Targets**

---

## 📊 SQL Case Studies

### 1. Running Totals
Calculate **monthly sales and orders** with a running total and cumulative performance over time.  

### 2. Moving Averages
Use **window functions** to calculate a **3-month moving average** for sales to smooth out trends.  

### 3. Before vs. After Analysis
Compare **sales performance before and after a cutoff date (2023-01-01)** to measure growth in products and categories.  

### 4. Data Cleaning & Categorization
Use **CASE WHEN** logic to create new product categories (e.g., grouping Books, Clothing, Others).  

### 5. Running Total with % Contribution
Calculate **year-to-date sales** and each month’s **percent contribution** to the annual total.  

### 6. Actual vs. Target Comparison
Compare **actual delivered sales** vs. **target sales** at the region level with **cumulative variances**.  

### 7. Growth Rate Analysis with LAG
Measure **month-over-month growth rates** using the `LAG()` window function.  

### 8. Ranking Functions
Compare `ROW_NUMBER`, `RANK`, and `DENSE_RANK` to rank products within each category by unit price.  

### 9. Customer Segmentation
Use `NTILE(4)` to divide customers into **quartiles** based on their total spend — identifying high-value vs. low-value customers.  

---

## ⚙️ Techniques Covered
- Aggregations (`SUM`, `COUNT`, `ROUND`)  
- **Window Functions**: `OVER()`, `LAG`, `NTILE`, `ROW_NUMBER`, `RANK`, `DENSE_RANK`  
- Conditional logic with **CASE WHEN**  
- Drilldown comparisons (Before vs After cutoff)  
- Cumulative calculations & moving averages  
- Customer segmentation by spend  

---

## 📄 How to Run
1. Create and load the `advanced_sql_db` database.  
2. Ensure all required tables (`orders`, `order_items`, `products`, `categories`, `customers`, `regions`, `sales_targets`) exist.  
3. Run queries in **MySQL Workbench / SQL Server / PostgreSQL** (syntax may need slight changes depending on RDBMS).  

---

## 🚀 Use Cases
These SQL queries can be applied in:  
- **Sales Analytics**  
- **Customer Segmentation**  
- **Revenue Growth Tracking**  
- **Target vs. Actual Business Performance**  
- **Data Cleaning & Categorization**  

---

## 📸 Example Queries Included
- Running Total & Percent of Annual Total  
- Moving Averages  
- Actual vs. Target Comparison  
- Growth Rate with LAG  
- Ranking Functions (ROW_NUMBER, RANK, DENSE_RANK)  
- Customer Segmentation with NTILE  
