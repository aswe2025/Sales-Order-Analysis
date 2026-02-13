
# 📊 Sales Order Analysis — Data Analytics Project

> End-to-end sales performance analysis using **Python, SQL, and Power BI** to transform raw transactional data into executive-ready business insights.

---

## 📌 Project Overview

The **Sales Order Analysis** project delivers a comprehensive evaluation of sales performance, revenue drivers, and profitability trends. The objective is to convert raw transactional data into structured business intelligence that supports strategic decision-making.

This project demonstrates a complete analytics workflow:

* Data cleaning and feature engineering in Python
* Advanced business querying in SQL
* Interactive dashboard development in Power BI
* Executive-level reporting and presentation

---

## 📂 Dataset Summary

The dataset (`orders.csv`) contains **9,994 records** and **16 attributes**, including:

### 🔹 Order Information

* Order ID
* Order Date
* Ship Mode
* Segment

### 🔹 Geographic Data

* Country
* City
* State
* Region

### 🔹 Product Details

* Category (Furniture, Office Supplies, Technology)
* Sub-Category
* Product ID

### 🔹 Financial Metrics

* Cost Price
* List Price
* Quantity
* Discount Percent

### 🔹 Engineered Fields

* Sale Price
* Profit
* Revenue

These attributes enable detailed revenue, profitability, and seasonal trend analysis.

---

## 🛠 Tools & Technologies

| Tool                                            | Purpose                                |
| ----------------------------------------------- | -------------------------------------- |
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data cleaning & EDA                    |
| **SQL (PostgreSQL / MySQL / SQL Server)**       | Business analysis & advanced querying  |
| **Power BI**                                    | Interactive dashboards & KPI reporting |
| **Jupyter Notebook**                            | Analysis environment                   |
| **Gamma**                                       | Executive presentation (PPT)           |
| **GitHub**                                      | Version control & documentation        |

---

## 🔄 Project Workflow

### 1️⃣ Exploratory Data Analysis (Python)

Using `Sales_Order_Analysis_.ipynb`:

* Loaded raw CSV data into Pandas
* Standardized column names to snake_case
* Handled null values and optimized data types
* Converted date fields to datetime format
* Engineered features such as Discount Amount, Sale Price, and Profit

---

### 2️⃣ SQL-Based Business Analysis

The cleaned dataset was migrated to a relational database to answer key business questions:

* 🔹 Top 10 highest revenue-generating products
* 🔹 Top 5 highest profit-generating products
* 🔹 Month-over-Month (MoM) comparison: 2022 vs 2023
* 🔹 Highest sales month per category
* 🔹 Revenue performance with discounts applied
* 🔹 Sub-category profit growth analysis

Advanced SQL techniques used:

* CTEs
* Window functions
* Aggregations
* Time-based calculations

---

## 📊 Key Insights

### 💰 Revenue by Category

Technology generated the highest total revenue, followed by Furniture and Office Supplies.

### 🏆 Top Revenue Product

`TEC-CO-10004722` emerged as the highest revenue and highest profit contributor.

### 🚚 Shipping Mode Impact

Standard Class shipping showed a higher average revenue per order compared to First Class.

### 📈 Growth Trends

* Strong YoY growth observed in February, April, and October 2023
* "Machines" sub-category recorded the highest profit growth (50.19%)

### ⚠ Profit Watch

"Paper" showed slight negative growth (-3.81%), suggesting pricing or cost structure review.

---

## 📊 Power BI Dashboard Overview

The `Sales Performance Dashboard.pbix` provides interactive visual analytics:

* 📌 KPI Scorecards (Total Sales, Total Profit, Quantity Sold)
* 📌 Category & Sub-Category Drill-Down
* 📌 Monthly & YoY Sales Trends
* 📌 Geographic Sales Mapping (U.S.)
* 📌 Shipping Mode & Discount Analysis

The dashboard enables stakeholders to explore performance dynamically and identify strategic opportunities.

---

## 📎 Project Files

```
orders.csv
Sales Order Data Analysis.ipynb
Sales Order SQL Query.sql
Sales Performance Dashboard.pbix
Solution.docx
Gamma Presentation (PPT)
```

---

## 🚀 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/your-username/sales-order-analysis.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook "Sales Order Data Analysis.ipynb"
```

### 4. Load Data into SQL Database

* PostgreSQL / MySQL / SQL Server

### 5. Execute SQL Queries

Run:

```
Sales Order SQL Query.sql
```

### 6. Open Power BI Dashboard

Open:

```
Sales Performance Dashboard.pbix
```

---

## 🎯 Business Recommendations

* Invest in high-performing Technology and Machines sub-categories
* Optimize pricing strategy for underperforming categories
* Align marketing campaigns with seasonal sales peaks
* Monitor profitability alongside revenue for sustainable growth

---

## 📌 Project Impact

This project demonstrates:

* End-to-end analytics lifecycle execution
* Strong SQL and data modeling skills
* Business-oriented data storytelling
* Executive-ready dashboard design
* Practical experience aligned with Data Analyst & Business Intelligence roles

---

⭐ If you found this project insightful, feel free to connect or provide feedback!

