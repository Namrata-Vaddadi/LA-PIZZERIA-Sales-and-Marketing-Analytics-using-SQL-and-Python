LA'PIZZERIA Pizza Sales Data Analysis
---


Welcome to the La'pizzeria Pizza Sales Data Analysis project! This repository contains a comprehensive data analysis of pizza sales at La'pizzeria, using SQL, Python, and Power BI to gain valuable business insights.

---

## Project Overview

La'pizzeria is a pizza shop specializing in a variety of pizza types and sizes. This project analyzes sales data collected over time to understand customer purchasing behaviors, popular pizza types, sales trends, and revenue generation.

---

## Repository Contents

- **`data/`**  
  Contains sample CSV data and a MySQL database dump file (`pizza_sales_dump.sql`) for database recreation.

- **`sql_queries/`**  
  Complete SQL queries used in the analysis, with documented explanations.

- **`notebooks/`**  
  Python Jupyter notebooks demonstrating exploratory data analysis, data cleaning, and visualization.

- **`reports/`**  
  PDF report summarizing SQL queries and their results.

---

## Data Description

- **orders.csv:** Information about customer orders including order IDs, dates, and times.

- **order_details.csv:** Details on pizzas ordered per order, including pizza IDs and quantities.

- **pizzas.csv:** Pizza inventory with pizza IDs, types, sizes, and prices.

- **pizza_types.csv:** Descriptions of pizza types, categories, and ingredients.

---

## Analysis Highlights

- Identification of top-selling pizza types and sizes.

- Sales trends over time (daily/monthly).

- Revenue analysis by pizza category and item.

- Insights into customer ordering patterns by time of day.


---

## How to Use This Repository

1. **Recreate Database:**  
   Use `pizza_sales_dump.sql` in the `data/` folder to recreate the MySQL database.

2. **Run SQL Queries:**  
   Explore the SQL queries in the `sql_queries/` folder to reproduce the analysis results.

3. **Python Analysis:**  
   Open the Jupyter notebooks in the `notebooks/` folder to perform exploratory data analysis, clean data, and visualize findings using Python.

---

## Tools & Technologies

- MySQL for data storage and query processing.

- Python (Pandas, Matplotlib) for data analysis and visualization.

---

## Project Structure

La-pizzeria-pizza-sales-project/
├── data/
│ ├── pizza_sales_dump.sql/
│ ├── orders.csv/
│ ├── order_details.csv/
│ ├── pizzas.csv/
│ └── pizza_types.csv/
├── notebooks/
│ └── pizza_sales_analysis.ipynb/
├── sql_queries/
│ └── pizza_sales_queries.sql/
├── reports/
│ └── analysis_report.pdf/
└── README.md/

---


Thank you for exploring LA'PIZZERIA's pizza sales data analysis project! Feel free to fork, explore, and build upon this work.

