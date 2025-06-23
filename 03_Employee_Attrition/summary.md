# 👥 Employee Attrition Analysis

## 🧠 Objective
To explore the HR dataset and uncover patterns behind employee attrition using **SQL-powered data analysis**. The goal was to identify key factors influencing attrition using structured queries and basic visual validation.

---

## 🛠️ Tools Used
- **SQL**: for querying, filtering, aggregating, and deriving insights from the dataset
- **Python**: pandas, seaborn for limited plotting and visual checks
- **Jupyter Notebook**: used primarily for running SQL queries within notebooks (via SQLite or similar engine)
- **Excel**: for initial data inspection

---

## 🔧 Key Steps
- Loaded the IBM HR dataset into a SQL environment and performed all primary analysis using **SQL queries**.
- Cleaned and filtered data through `WHERE`, `CASE`, and conditional logic directly in SQL.
- Used `GROUP BY`, `ORDER BY`, and `JOIN` operations to compare attrition across age, departments, income levels, etc.
- Derived category-based summaries such as attrition % by department, gender, and job role.
- Minimal use of Python for quick visualizations of SQL output (bar plots and heatmaps).

---

## 📊 Key Insights
- 🔄 Employees with **OverTime = Yes** had the highest attrition rate.
- 👶 Younger employees (ages 25–35) were the most likely to leave.
- 🧑‍💼 Departments like **Sales** and **Human Resources** experienced more exits.
- 📉 **Low monthly income** and **low job satisfaction** were common among those who left.
- 💔 Single employees and those with lower environment satisfaction were more prone to attrition.

---

## 📌 Deliverables
- `Employee Attrition Analysis.ipynb`: Jupyter notebook running and displaying SQL-based queries and results.
- `summary.md`: This documentation file.
- `WA_Fn-UseC_-HR-Employee-Attrition.csv`: Original dataset used in analysis.

---

## ✅ Learnings & Outcomes
- Practiced performing **exploratory data analysis using SQL**, a shift from my previous Python-based projects.
- Strengthened SQL skills including **data filtering, conditional aggregation, and analytical query design**.
- Learned how to structure queries for behavioral analysis and derive meaningful insights purely through SQL logic.

> 📎 This project was a step outside my Python comfort zone — and it helped me become more confident in SQL for real-world data exploration and insight generation.

