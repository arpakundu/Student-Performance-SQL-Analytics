# 🚀 Student Performance Analytics Pipeline (SQL & Python)

This project implements a **beginner-friendly, analytics-focused data engineering pipeline** using **Python and SQL** to analyze factors influencing student academic performance.

The pipeline ingests raw CSV data, performs basic data validation, loads data into a SQL analytics engine, and executes SQL queries to generate meaningful insights.
The project emphasizes **data ingestion, structured querying, and analytics enablement**, making it suitable as a **capstone-style project for a fresher-level Data Engineering role**.

## 🎯 Business Problem

Educational datasets often exist as raw CSV files that are not directly usable for analysis.
Institutions and analysts need a **reliable and structured way to explore performance drivers** such as study hours, sleep patterns, attendance, and parental involvement.

### Objective:

* Load raw student performance data into a SQL environment
* Enable analytics using SQL queries
* Identify key factors affecting exam scores
* Demonstrate an end-to-end analytics workflow using Python and SQL

## 📊 Dataset

* **Name:** Student Performance Factors
* **Source:** Kaggle
* **Type:** Structured CSV dataset
* **Records:** 1,000+ student entries

🔗 Dataset link:
https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

### Key Attributes:

* Study habits (Hours_Studied, Sleep_Hours)
* Academic background (Previous_Scores, Attendance)
* Social & environmental factors (Parental_Involvement, Internet_Access)
* Outcome variable (Exam_Score)

## ⚙️ Project Workflow

1. **Data Ingestion**

   * Load raw CSV data using Pandas

2. **Data Validation**

   * Inspect missing values
   * Verify column types and ranges

3. **SQL Analytics Setup**

   * Register dataset as a SQL table using DuckDB
   * No external database setup required

4. **Analytics & Querying**

   * Use SQL for grouping, aggregation, and filtering
   * Analyze relationships between student attributes and exam scores

5. **Visualization**

   * Plot trends to support SQL-based insights

## 🧠 Data Quality Checks

Basic validation steps are applied before analysis:

* Missing value inspection
* Range checks for numerical columns
* Categorical value consistency review

These checks ensure the dataset is suitable for analytics and reflect early-stage data quality practices.

## 📈 Analytics Performed

The project answers questions such as:

* How do study hours impact exam performance?
* What is the relationship between sleep duration and exam scores?
* Does parental involvement influence academic outcomes?
* How does attendance correlate with exam results?
* Do extracurricular activities affect performance?

All analytics are performed using **SQL queries**, reflecting real-world analytical workflows.

## 📂 Outputs

* SQL query results displayed in tabular format
* Visualizations for key trends
* Reproducible Jupyter Notebook workflow

## 🛠️ Tech Stack

* Python
* Pandas
* SQL
* DuckDB
* Matplotlib / Seaborn
* Jupyter Notebook

## 🧠 Key Learnings

* Loading structured data for analytics
* Using SQL for data exploration and aggregation
* Combining Python and SQL in a single workflow
* Performing basic data validation
* Translating data into actionable insights

## 📁 Repository Structure

```
Student-Performance-SQL-Analytics/
│
├── StudentPerformanceFactors.csv
├── student_performance.ipynb
├── README.md
└── requirements.txt
```

## 👩‍💻 Author

**Arpa Kundu**

## 📜 License

MIT License
