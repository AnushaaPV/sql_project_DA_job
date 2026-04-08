# 📊 SQL Project: Data Analyst Job Market Analysis

> Exploring top-paying roles, in-demand skills, and where high demand meets high salary in the data analytics industry.

---

## 📌 Introduction

This project dives deep into the **Data Analyst job market** using SQL to uncover meaningful insights about job postings, required skills, and salary trends. The goal was to answer practical questions that any aspiring or experienced data analyst would ask — *What skills should I learn? Which roles pay the most? Where is the demand highest?*

All analysis was done by querying a rich dataset of job postings using structured SQL queries, and findings are documented here along with the key takeaways.

🔍 SQL queries used in this project can be found in the [`project_sql/`](./project_sql/) folder.

---

## 🗂️ Background

The motivation behind this project was personal — to better understand the data analyst job landscape and make smarter decisions about skill development and job searching.


The analysis focused on answering these key questions:
1. What are the top-paying Data Analyst jobs?
2. What skills are required for these top-paying jobs?
3. What skills are most in demand for Data Analysts?
4. Which skills are associated with higher salaries?
5. What are the most optimal skills to learn (high demand + high pay)?

---

## 🛠️ Tools I Used

| Tool | Purpose |
|------|---------|
| **SQL** | Core language for all data querying and analysis |
| **PostgreSQL** | Database management system used to store and run queries on job posting data |
| **Visual Studio Code** | Primary editor for writing and executing SQL queries |
| **Git & GitHub** | Version control and project sharing |

---

## 🔍 The Analysis

Each SQL query was designed to investigate a specific aspect of the job market. Here's a summary of the five key analyses performed:

### 1. Top-Paying Data Analyst Jobs
Identified the highest-paying remote Data Analyst positions by filtering job postings with non-null salary values and sorting by average yearly salary.

### 2. Skills for Top-Paying Jobs
Joined job postings with skills data to reveal what employers value most in high-compensation roles. SQL, Python, and Tableau were consistently at the top.

### 3. Most In-Demand Skills
Counted skill frequency across all Data Analyst job postings to find the most requested competencies in the market.

### 4. Skills with Higher Salaries
Calculated the average salary associated with each skill to identify which specializations command a premium — including tools like Snowflake, Spark, and cloud platforms.

### 5. Optimal Skills (Demand + Salary)
Combined demand and salary data to find skills that offer both high market demand and strong earning potential — giving a balanced view of what's worth learning.

---

## 💡 What I Learned

Working through this project strengthened several SQL competencies and provided real insight into the job market:

- **Advanced SQL techniques** — Gained hands-on experience with CTEs (Common Table Expressions), window functions, and multi-table JOINs to perform complex, multi-step analyses.
- **Aggregation & Grouping** — Used `GROUP BY`, `COUNT()`, `AVG()`, and `ROUND()` extensively to summarize and compare data across dimensions.
- **Filtering with precision** — Applied `WHERE` clauses and subqueries to drill into specific job types (e.g., remote roles, Data Analyst titles) and eliminate noise.
- **Real-world problem solving** — Translated open-ended business questions into concrete SQL queries and interpreted the results meaningfully.
- **Job market awareness** — Developed a practical understanding of which skills are most valued, which roles pay the most, and how to position oneself competitively in the data analytics field.

---

## ✅ Conclusions

This analysis of the 2025 Data Analyst job market led to several actionable insights:

1. **SQL is non-negotiable** — It appears in the majority of top-paying job listings and is the most in-demand skill overall.
2. **Python and Tableau round out the core toolkit** — These two consistently appear alongside SQL for both high-demand and high-salary roles.
3. **Specialized skills pay more** — Tools like Snowflake, Spark, and cloud platforms (AWS, Azure) are associated with significantly higher average salaries.
4. **Optimal skills balance demand and pay** — For maximum career ROI, focusing on SQL, Python, Tableau, and cloud skills offers the best combination of employability and earning potential.

> **Final thought:** This project not only sharpened my SQL skills but also gave me a data-driven roadmap for navigating the data analyst job market. The insights here can guide any aspiring analyst on where to focus their learning efforts.