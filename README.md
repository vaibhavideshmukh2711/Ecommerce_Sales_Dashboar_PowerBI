# E-commerce Sales Analysis & Interactive Dashboard

## 📌 Project Overview

This project presents an **end-to-end E-commerce Sales Analysis** using **SQL, Python, and Power BI**. The goal of the project is to analyze sales performance, identify business trends, and build an interactive dashboard to support **data-driven decision-making**.

The project demonstrates the complete analytics workflow — from raw data extraction and cleaning to exploratory analysis and executive-level dashboarding — similar to real-world business and product analytics tasks.

---

## 🎯 Business Objectives

* Analyze **Year-to-Date (YTD) sales, profit, quantity, and profit margins**
* Identify **top and bottom performing products**
* Understand **regional sales distribution** and customer segments
* Track **category-wise performance and YoY trends**
* Enable stakeholders to monitor KPIs through an **interactive dashboard**

---

## 🛠 Tools & Technologies Used

* **SQL (MySQL)** – Data extraction, joins, aggregations, KPI calculations
* **Python** – Data cleaning and exploratory data analysis (EDA)

  * Pandas
  * NumPy
  * Matplotlib / Seaborn
* **Power BI** – Interactive dashboard, DAX measures, data modeling
* **Excel** – Initial validation and quick analysis

---

## 📂 Project Structure

```
Ecommerce-Sales-Analysis/
│
├── sql/
│   └── ecommerce_queries.sql        # SQL queries for analysis
│
├── python/
│   └── Ecommerce_project.ipynb      # Data cleaning & EDA in Python
│
├── powerbi/
│   └── Ecommerce_Sales_Dashboard.pbix
│
├── images/
│   └── EcommerceSales_Dashboard.png # Dashboard preview
│
└── README.md
```

---

## 🔍 Data Analysis Workflow

### 🔗 Python–SQL Connectivity

* Established a direct connection between **Python and MySQL** using appropriate database connectors
* Executed **SQL queries within Python** to fetch transactional sales data
* Automated data extraction into Pandas DataFrames for further cleaning and analysis
* Ensured data consistency between database outputs and analytical datasets

This approach simulates a **real-world analytics setup**, where analysts pull live data from databases into Python for analysis and reporting.

### 1️⃣ Data Extraction (SQL via Python)

* Connected Python to a **MySQL database** to retrieve raw e-commerce sales data

* Executed **joins, filters, aggregations, and GROUP BY queries** directly from Python

* Calculated key metrics such as:

  * YTD Sales, Profit, and Quantity
  * Category- and product-level KPIs
  * Region- and shipping-type performance

* Retrieved transactional sales data using **SQL queries**

* Used **joins, filters, aggregations, and GROUP BY** to calculate:

  * YTD Sales & Profit
  * Quantity sold
  * Category and product-level KPIs
  * Region and shipping-type performance

### 2️⃣ Data Cleaning & EDA (Python)

* Cleaned and transformed data using **Pandas**
* Handled missing values and data inconsistencies
* Performed **EDA** to uncover:

  * Sales and profit trends
  * Category-wise performance
  * High and low revenue products
  * Regional sales patterns

### 3️⃣ Dashboard Development (Power BI)

* Built an **interactive Power BI dashboard** with:

  * KPI cards (Sales, Profit, Quantity, Profit Margin)
  * Category-wise and product-wise performance tables
  * Top & Bottom 5 products by YTD sales
  * Region-wise and shipping-type sales distribution
  * Segment filters (Consumer, Corporate, Home Office)

---

## 📊 Key Insights

* Office Supplies contributed the **highest YTD sales**, while Technology showed a decline YoY
* West region generated the **highest sales share**, followed by East and Central
* Standard Class shipping dominated order volume
* Identified low-performing products with minimal revenue contribution
* Profit margin increased despite a slight drop in total sales

---

## 📈 Dashboard Preview

![E-commerce Sales Dashboard](images/EcommerceSales_Dashboard.png)

---

## 💡 Business Impact

* Helps stakeholders track **real-time KPIs** and performance
* Enables identification of **growth opportunities and weak areas**
* Supports **strategic decisions** related to product mix, regions, and logistics

---

## 🚀 Learnings & Takeaways

* Hands-on experience with **end-to-end data analytics lifecycle**
* Strengthened SQL skills for business-focused analysis
* Improved data storytelling through dashboards
* Practical exposure to translating raw data into **actionable insights**

---

## 🔗 Links

* **Python Notebook:** [View Analysis](python/Ecommerce_project.ipynb)
* **Power BI Dashboard:** Included in repository

---

## 👩‍💻 Author

**Vaibhavi Deshmukh**
Data Analyst | SQL | Python | Power BI
[LinkedIn](https://www.linkedin.com/in/vaibhavi-deshmukh-963138346)
[GitHub](https://github.com/vaibhavideshmukh2711)







