# 📊 Customer Shopping Behavior – End-to-End Data Analytics Project

## 📌 Project Overview

This project simulates a **corporate-grade end-to-end data analytics workflow**, demonstrating how raw transactional data can be transformed into **strategic business intelligence** using Python, SQL, and Power BI.

The objective is to showcase practical skills across the complete analytics lifecycle:

* Data preparation and feature engineering
* Relational database integration
* Business-driven SQL analysis
* Interactive dashboarding
* Insight communication through reports and presentations

---

## 🎯 Key Objectives & Deliverables

### ✅ Data Preparation, Modeling & Exploratory Data Analysis (Python)

* Loaded and explored a dataset of **3,900 customer transactions**
* Handled missing values (category-wise median imputation for review ratings)
* Standardized column naming (snake_case)
* Engineered new features:

  * `age_group` using quartile-based segmentation
  * `purchase_frequency_days` from categorical frequency labels
* Validated data consistency (discount vs promo code)
* Prepared final analytics-ready table structure

---

### ✅ Data Analysis (SQL)

Simulated real-world business analytics by writing SQL queries to answer:

* Revenue comparison by gender
* Impact of subscriptions on spending behavior
* Top-rated and most discounted products
* Shipping type vs average order value
* Customer segmentation (New / Returning / Loyal)
* Product performance within each category
* Revenue contribution by age group
* Repeat buyers vs subscription likelihood

Databases supported:

* PostgreSQL
* MySQL
* MS SQL Server

---

### ✅ Visualization & Insights (Power BI)

Built an **interactive executive dashboard** featuring:

* KPI cards:

  * Total customers
  * Average purchase amount
  * Average review rating

* Visual analytics:

  * Revenue by category
  * Sales by category
  * Revenue by age group
  * Sales by age group
  * Subscription distribution

* Slicers:

  * Gender
  * Product size
  * Subscription status

The dashboard enables stakeholders to explore customer behavior dynamically and identify high-value segments.

---

### ✅ Report & Presentation

* Created a structured project report summarizing:

  * Methodology
  * Data transformations
  * SQL findings
  * Business insights
  * Strategic recommendations

* Prepared a presentation deck (using Gamma AI) to communicate:

  * Key trends
  * Revenue drivers
  * Customer loyalty patterns
  * Optimization opportunities

---

## 🔄 Project Workflow

```
Raw CSV Dataset
      ↓
Python (Cleaning + Feature Engineering + EDA)
      ↓
SQL Database (PostgreSQL / MySQL / SQL Server)
      ↓
Business Analysis using SQL Queries
      ↓
Power BI Data Model
      ↓
Interactive Dashboard
      ↓
Business Report & Presentation
```

---

## 🛠️ How to Use This Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI.git
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

---

### 2️⃣ Run the Python notebook

Open:

```
customer_shopping_behaviour.ipynb
```

This notebook performs:

* Data import
* Exploration & cleaning
* Feature engineering
* SQL database connection
* Data loading into database

---

### 3️⃣ Load data into SQL database

Choose your DB:

#### PostgreSQL

Uses SQLAlchemy + psycopg2

#### MySQL

Uses SQLAlchemy + pymysql

#### MS SQL Server

Uses SQLAlchemy + pyodbc

The notebook already contains ready-to-use connection templates for all three.

---

### 4️⃣ Run SQL analysis

Open:

```
customer_behaviour_questionaires.sql
```

Execute queries to generate business insights.

---

### 5️⃣ Open Power BI dashboard

Open:

```
Customer_Behaviour_Dashboard.pbit
```

* Connect to your SQL database
* Refresh data
* Interact with dashboard visuals

---

### 6️⃣ Create report & presentation

* Summarize findings in a project report
* Build stakeholder presentation (Gamma AI / PowerPoint / Google Slides)

---

## 🧪 Dataset Summary

* Rows: 3,900
* Columns: 18 → 19 (after feature engineering)
* Domains:

  * Demographics
  * Transactions
  * Reviews
  * Subscription behavior
  * Logistics
  * Payment patterns

---

## 📈 Skills Demonstrated

* Data cleaning & transformation
* Feature engineering
* SQL analytics (aggregations, window functions, CTEs)
* Database integration with Python
* Business intelligence dashboard design
* KPI definition
* Analytical storytelling

