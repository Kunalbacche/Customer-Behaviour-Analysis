# Customer Behavior Analysis using Python, PostgreSQL & Power BI

## 📌 Project Overview

This project is an end-to-end data analytics solution that analyzes customer behavior to uncover meaningful insights into customer demographics, purchasing patterns, and business performance. The project demonstrates the complete data analytics workflow, including data preprocessing, exploratory data analysis (EDA), database management, SQL querying, and interactive dashboard creation.

The primary objective is to transform raw customer data into actionable business insights that can help organizations improve customer engagement, optimize marketing strategies, and support data-driven decision-making.

---

## 🎯 Objectives

* Clean and preprocess raw customer data.
* Perform Exploratory Data Analysis (EDA) to identify trends and patterns.
* Store the processed dataset in a PostgreSQL database.
* Analyze customer behavior using SQL queries.
* Build an interactive Power BI dashboard for business reporting.
* Generate insights to support strategic business decisions.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Environment:** Jupyter Notebook
* **Python Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Database:** PostgreSQL
* **Query Language:** SQL
* **Visualization Tool:** Power BI
* **Dataset Format:** CSV

---

## 📂 Project Structure

```text
Customer-Behavior-Analysis/
│
├── data/
│   ├── customer_data.csv
│   └── cleaned_customer_data.csv
│
├── notebooks/
│   └── Customer_Behavior_Analysis.ipynb
│
├── sql/
│   ├── database_schema.sql
│   ├── import_data.sql
│   └── analysis_queries.sql
│
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   └── eda_visualizations.png
│
├── README.md
└── requirements.txt
```

---

## 📊 Workflow

### 1. Data Collection

* Imported customer dataset in CSV format.

### 2. Data Cleaning & Preprocessing

* Removed duplicate records.
* Handled missing values.
* Corrected data types.
* Standardized categorical values.
* Prepared the dataset for analysis.

### 3. Exploratory Data Analysis (EDA)

* Customer demographic analysis.
* Purchase behavior analysis.
* Distribution of customer attributes.
* Correlation analysis.
* Data visualization using Matplotlib and Seaborn.

### 4. PostgreSQL Database

* Created database and tables.
* Imported cleaned dataset into PostgreSQL.
* Managed structured customer data for analysis.

### 5. SQL Analysis

Performed SQL queries to answer business questions using:

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* HAVING
* Aggregate Functions
* CASE Statements
* JOINs (if applicable)
* Common Table Expressions (CTEs)

### 6. Power BI Dashboard

Developed an interactive dashboard featuring:

* Customer Overview
* Customer Demographics
* Purchase Trends
* Sales KPIs
* Revenue Analysis
* Interactive Filters & Slicers
* Charts and Visualizations

---

## 📈 Key Insights

* Identified customer segments based on demographic characteristics.
* Analyzed purchasing behavior across different customer groups.
* Discovered trends in customer engagement and sales performance.
* Highlighted key business metrics through interactive dashboards.
* Enabled data-driven decision-making using SQL queries and visual analytics.

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* SQL Query Writing
* PostgreSQL Database Management
* Business Intelligence
* Dashboard Design
* Data Visualization
* KPI Reporting
* Analytical Thinking

---

## 📸 Dashboard Preview

> Add screenshots of your Power BI dashboard inside the `images/` folder and reference them here.

Example:

```markdown
![Dashboard](images/dashboard.png)
```

---

## ▶️ How to Run the Project

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook and execute all cells.
4. Import the cleaned dataset into PostgreSQL.
5. Run the SQL scripts provided in the `sql/` folder.
6. Open the Power BI (`.pbix`) file and connect it to your PostgreSQL database.
7. Refresh the data and explore the interactive dashboard.

---

## 📌 Future Enhancements

* Automate data refresh using scheduled pipelines.
* Integrate cloud-based databases.
* Add predictive analytics using machine learning.
* Deploy the dashboard to the Power BI Service.
* Build real-time reporting capabilities.

---

## 👤 Author

**Kunal Bacche**

If you found this project useful, feel free to ⭐ the repository and connect with me for feedback or collaboration.
