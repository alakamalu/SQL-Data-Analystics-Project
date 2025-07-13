# 🧠 Advanced SQL Analytics Project – Customer & Product Insights

Welcome to the **Advanced SQL Analytics Project**, a real-world end-to-end data analytics solution powered entirely by **SQL**. This project simulates how data analysts work with large datasets to generate actionable insights, build performance KPIs, and deliver clean, ready-to-use reporting views for business stakeholders and dashboard tools (e.g., Power BI, Tableau).


## 📌 Project Objectives

* ✅ Perform **deep customer and product analysis** using raw transactional data
* ✅ Implement **advanced SQL techniques** like CTEs, segmentation logic, and KPI computation
* ✅ Create **modular and reusable SQL scripts** for exploration, transformation, and reporting
* ✅ Build **final reporting views** for use by analysts or dashboard developers
* ✅ Demonstrate a full **analytics pipeline** using SQL from raw data to insight delivery


## 📊 Key Features

### 🔹 Customer Report View (`gold.report_customers`)

* Customer demographics & identifiers
* Customer segmentation by:

  * **Spending behavior**: New / Regular / VIP
  * **Age group**: <20, 20–29, 30–39, etc.
* KPIs:

  * Recency (months since last order)
  * Average order value (AOV)
  * Average monthly spend

### 🔹 Product Report View (`gold.report_products`)

* Product metadata: name, category, subcategory
* Product segmentation by revenue performance: High / Mid / Low
* KPIs:

  * Average order revenue
  * Average monthly revenue
* Aggregations:

  * Total orders, customers, quantity, sales


## 🛠️ SQL Techniques Used

* CTEs (Common Table Expressions)
* Aggregations & Window Functions
* Data segmentation (CASE WHEN logic)
* Date difference calculations
* Derived KPIs
* View creation for reporting layers

## 🗂️ Project Structure

```bash
sql-analytics-project/
├── 📁 datasets/
│   ├── gold.dim_customers.csv
│   ├── gold.dim_products.csv
│   └── gold.fact_sales.csv
│
├── 📁 scripts/
│   ├── 00_init_database.sql
│   ├── 01_database_exploration.sql
│   ├── 02_dimensions_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_ranking_analysis.sql
│   ├── 07_change_over_time_analysis.sql
│   ├── 08_cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_part_to_whole_analysis.sql
│   ├── 12_report_customers.sql
│   └── 13_report_products.sql
│
├── LICENSE
└── README.md  ← you are here
```

## 📎 Tools & Environment

* SQL Server (or any modern RDBMS)
* Power BI / Tableau (for visualization)
* GitHub (for collaboration and versioning)


## 🤝 Acknowledgment

This project is inspired by a practical YouTube tutorial series on SQL analytics. It has been extended and customized to reflect real-world reporting practices.


## 🙋‍♀️ About Me

Hi! I’m Alaka, an aspiring **Data Analyst** passionate about turning data into actionable insight. This project is part of my learning journey into business analytics using SQL.

Feel free to check out my other projects or connect with me on [LinkedIn](https://www.linkedin.com/in/alakap01).


## ⭐ If you found this helpful

Star ⭐ the repo, share it, or drop a message—your support means a lot!

