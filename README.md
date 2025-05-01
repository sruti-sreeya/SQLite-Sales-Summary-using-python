# 🛍️ SQLite Sales Summary

This project demonstrates how to use **SQL inside Python** to analyze sales data stored in a **SQLite database** and visualize key metrics using **pandas** and **matplotlib**, all in a single Jupyter Notebook.

---

## 📌 Objective
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Create and populate a **SQLite database** with sample sales data.
- Run SQL queries using Python (`sqlite3`).
- Calculate:
  - Total quantity sold per product
  - Total revenue per product
- Display the summary using `print()` statements.
- Visualize the revenue per product using a bar chart.

---

## 🗂️ Project Structure
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| File Name                   | Description                                           |
|----------------------------|-------------------------------------------------------|
| SQLite Sales Summary.ipynb | Jupyter Notebook with all steps (create, query, plot) |
| sales_data.db              | SQLite database file (auto-generated)                 |
| sales_chart.png            | Revenue bar chart image (auto-generated)              |
| README.md                  | Project overview and usage instructions               |

---

## ▶️ How to Run
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. **Install the required libraries** (if not already installed):
   ```bash
   pip install pandas matplotlib
Open the Jupyter Notebook:
jupyter notebook "SQLite Sales Summary.ipynb"

Run each cell in order:

Create and insert sample data into the SQLite database

Run SQL queries to summarize the data

Display and visualize the results

🛠️ Libraries Used
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
sqlite3 (standard Python library)

pandas

matplotlib

📈 Sample Output
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Printed sales summary showing total quantity and revenue per product

📊 Bar chart (sales_chart.png) showing revenue by product

