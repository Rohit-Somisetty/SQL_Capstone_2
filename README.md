# 🧠 SQL Capstone Part 2: HR Analytics with SQL

This project continues from Part 1, shifting the analysis to SQL. Using `sqlite3`, we explore employee attrition trends and performance factors using structured queries on the HR dataset.

---

## 🎯 Objectives

- Calculate overall and segmented attrition rates using SQL
- Analyze attrition trends by Gender, Department, Age, Tenure, and Income
- Investigate drivers of early attrition (< 5 years)
- Use SQL to uncover trends not easily visible in flat analysis

---

## 🧰 Tools & Technologies

- **Language:** SQL (SQLite3)  
- **Environment:** Jupyter Notebook (via `sqlite3` and `pandas`)  
- **Data Interface:** SQL queries executed in Python notebook

---

## 📁 Files

Capstone_1_Part2/
├── SQL_Capstone_2.ipynb # Jupyter Notebook for SQL analysis
├── WA_Fn-UseC_-HR-Employee-Attrition.csv # Input dataset
└── README.md


---

## 📌 Analysis Workflow

### ✅ Step 1: SQLite DB Creation
- Loaded CSV data into a SQLite3 in-memory database using Python
- Verified schema and row count

### ✅ Step 2: Attrition Metrics by Segment
- Calculated overall attrition percentage
- Analyzed attrition by:
  - Gender
  - Department
  - Age Groups
  - Monthly Income (by JobLevel & Department)
  - Tenure (Years at Company)

### ✅ Step 3: Investigating Attrition Drivers
- Queried data to answer:
  - Why more people over 50 leave than those aged 40–50
  - Why higher-paid employees still leave
  - What drives employees with < 5 years tenure to leave

### ✅ Step 4: Communication
- Documented rationale for each query using markdown
- Explained sample output tables inline
- Queries were commented and optimized for clarity

---

## 🔍 Sample Insights

- Males had a slightly higher attrition rate than females
- Employees in Sales and R&D showed higher departure counts
- Attrition is notably higher in employees with under 5 years of service
- High attrition was found even among employees with high income, suggesting non-monetary factors matter

---
