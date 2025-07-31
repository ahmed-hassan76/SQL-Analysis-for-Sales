# SQL-Analysis-for-Sales
# 🎵 Chinook SQL-Based Sales Analysis in Jupyter Notebook

This project explores product sales and business insights using SQL queries on the Chinook Database within a Python (Jupyter Notebook) environment.

---

## 🔍 Project Objectives

- Use SQL to analyze sales, revenue, and customer trends from a relational database
- Perform analysis directly in Jupyter Notebook using Python and SQLite
- Visualize key findings using matplotlib and seaborn

---

## 📂 Dataset

- **Chinook.sqlite** — A sample music store database containing info on customers, invoices, tracks, and more
  
---

## ✅ Key Analyses

| Business Question                    | SQL Technique           |
|-------------------------------------|--------------------------|
| Top-selling tracks                  | JOIN + GROUP BY + SUM    |
| Revenue by country                  | GROUP BY                 |
| Monthly revenue performance         | `strftime()` for dates   |
| Ranking countries by revenue        | Window Function (`RANK`) |

---

## 🛠 Tools & Libraries

- `sqlite3`
- `pandas`
- `matplotlib`
- `seaborn`
- Jupyter Notebook
