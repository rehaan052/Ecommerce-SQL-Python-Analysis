# Ecommerce-SQL-Python-Analysis
End-to-end ecommerce data analysis using MySQL and Python, focused on extracting business insights from real-world relational data.

# 🛒 Ecommerce SQL & Python Analysis

A complete **end-to-end data analysis project** on an ecommerce dataset using **MySQL and Python**.
This project focuses on extracting business insights from raw transactional data through **SQL querying**, **data wrangling**, and **exploratory data analysis (EDA)**.

---

## 📌 Project Objective

To analyze an ecommerce database and answer real-world business questions related to:

* Customer distribution
* Orders and payments
* Product and seller behavior
* Geographic insights

This project is designed to demonstrate **practical SQL skills** and **Python-based data analysis**, aligned with industry and recruiter expectations.

---

## 🗂️ Dataset Overview

The database consists of multiple relational tables:

* **customers** – customer details and location
* **orders** – order-level information
* **order_items** – product-level order details
* **payments** – payment methods and values
* **products** – product metadata
* **sellers** – seller information
* **geolocation** – geographic mapping data

> All tables are connected using primary–foreign key relationships, simulating a real production database.

---

## 🛠️ Tools & Technologies Used

* **MySQL** – data storage, querying, joins, aggregations
* **Python** – data analysis and transformation
* **Pandas** – converting SQL results into DataFrames
* **Jupyter Notebook** – interactive analysis
* **Git & GitHub** – version control and project sharing

---

## 🔍 Key Analysis Performed

### SQL Analysis

* Selecting and filtering data
* Aggregations using `GROUP BY`
* Multi-table joins
* Subqueries
* Business-focused queries

Example:

```sql
SELECT DISTINCT customer_city
FROM customers;
```

---

### Python + SQL Integration

* Connected MySQL database to Python
* Executed SQL queries using Python
* Converted query results into Pandas DataFrames
* Performed exploratory analysis on results

Example:

```python
import pandas as pd

df = pd.read_sql("SELECT DISTINCT customer_city FROM customers", conn)
```

---

## 📊 Sample Insights

* Identified cities with the highest number of customers
* Analyzed geographic distribution of orders
* Explored customer behavior across regions
* Evaluated payment patterns

> Insights are derived directly from structured SQL queries and validated using Python.

---

## 📁 Project Structure

```
Ecommerce-SQL-Python-Analysis/
│
├── analysis.ipynb        # Main Jupyter notebook
├── sql_queries/          # SQL scripts used in analysis
├── README.md             # Project documentation
└── assets/               # Images / plots (if any)
```

---

## 🚀 How to Run This Project

1. Clone the repository

```bash
git clone https://github.com/your-username/Ecommerce-SQL-Python-Analysis.git
```

2. Set up MySQL and import the database

3. Install required Python libraries

```bash
pip install pandas mysql-connector-python
```

4. Open `analysis.ipynb` in Jupyter Notebook

5. Update database connection credentials and run the notebook

---

## 🎯 Skills Demonstrated

* SQL querying on relational databases
* Database-to-Python integration
* Data cleaning and exploration
* Analytical thinking and business insight generation
* Project structuring and documentation

---

## 📌 Future Improvements

* Add advanced analytical queries
* Create visualizations (Matplotlib / Seaborn)
* Build dashboards (Tableau / Power BI)
* Automate analysis pipeline

---

## 👤 Author

**Rehaan**
Aspiring Data Analyst | SQL | Python | Data Analytics

📎 GitHub: [https://github.com/your-username](https://github.com/rehaan_052)
📎 LinkedIn: [https://linkedin.com/in/your-profile](https://linkedin.com/in/ibrahim-rehaan)

---

⭐ If you found this project useful, feel free to star the repository!

