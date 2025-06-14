# 📱 Google Play Store Apps Analysis

## 🧠 Objective
To clean, transform, and analyze the Google Play Store dataset to uncover insights into app ratings, installs, categories, and pricing behavior across thousands of Android apps.

---

## 🛠️ Tools Used
- **Python**: pandas, numpy, seaborn, matplotlib
- **Jupyter Notebook**: for step-by-step EDA and cleaning

---

## 🔧 Key Steps
- Cleaned severe anomalies like ratings above 5 and improperly formatted install counts.
- Filled missing ratings using grouped mean values based on `Installs` category.
- Dropped apps with no installs, as they provided no analytical value.
- Engineered new features like `Size_MB` and categorized install counts for deeper grouped analysis.
- Handled special characters, type conversions, and outlier detection.

---

## 📊 Key Insights
- 📉 Most apps had ratings between 3.5 and 4.5, with a visible skew toward higher ratings.
- 💰 Free apps were significantly more common and better rated than paid ones.
- 📈 Categories like **Education**, **Entertainment**, and **Productivity** had the highest installs.
- 📉 Apps with more than 1M installs were fewer in number but showed consistently higher ratings.
- 🧹 Outliers like apps with absurd pricing or no installs were cleaned for better accuracy.

---

## 📌 Deliverables
- `Google Play Store Apps Analysis.ipynb`: Full notebook with code, cleaning steps, and visualizations.
- `summary.md`: This documentation file.
- `googleplaystore.xlsx`: Raw dataset (included in this folder for reference)

---

## ✅ Learnings & Outcomes
- This project sharpened my skills in **data cleaning**, **group-based imputation**, and **feature engineering**.
- Helped me understand the importance of treating each column uniquely during preprocessing.
- Reinforced the need to **look beyond surface-level stats** and dive into grouped behaviors and outlier treatment.

> 📎 This was one of my most hands-on experiences dealing with dirty, real-world app data — great practice for any data role involving consumer or product analytics.
