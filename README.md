# HR-ANALYTICS-DASHBOARD-
# 📊 HR Analytics Dashboard using Power BI  
**Portfolio Project**

---

## 🧩 Project Overview

The success of any organization is significantly influenced by its workforce. Accurate employee data analysis, effective performance tracking, and well-informed HR strategies contribute to maintaining a competitive edge while minimizing costs. In this project, I developed a comprehensive **HR Analytics Dashboard using Power BI** to provide actionable insights into employee promotions, layoffs, satisfaction, performance, and department-level impacts.

This project simulates how organizations can leverage **Business Intelligence (BI)** to optimize HR decisions and strategic planning.

---

## 🔍 Objectives

This analysis aims to answer the following questions:

- How many employees have not been promoted in the last 10+ years?
- What is the overall years of service distribution?
- What is the distribution of job levels (1 to 5)?
- What is the distance-to-office distribution among employees?
- Which departments will be most affected by promotions or layoffs?
- What are the levels of job satisfaction?
- What percentage of employees work overtime?
- What is the total count and distribution of promotions/layoffs across job roles?
- Who are the specific employees eligible for promotion or layoff?

---

## 🛠️ Tools and Technologies

- **Power BI (Desktop)** – Dashboard creation, data modeling & visualization
- **Power Query** – Data cleaning & transformation
- **Excel / PowerPoint** – Background design
- **Coolors.co** – Color palette generation
- **Data Source** – Kaggle HR Analytics Dataset

---

## 📥 Data Collection

- `HR Analytics Data` – 1470 rows × 35 columns  
- `HR Employee Data` – 1470 rows × 2 columns  
- Shared key: `EmployeeNumber`

---

## 🧹 Data Cleaning & Transformation

Steps performed in Power Query:

- Checked and confirmed no nulls or invalid data types
- Created measures: total employees, gender distribution
- Created conditional columns for:
  - Promotion eligibility (≥10 years since last promotion)
  - Layoff eligibility (≥18 years in service)
  - Distance to office (Very Far, Close, Very Close)
  - Job satisfaction (High, Medium, Low)
  - Performance rating (High vs. Low)

After cleaning:
- `HR Analytics` table: 44 columns  
- `HR Employee` table: unchanged

---

## 📊 Exploratory Data Analysis

**Visual Components:**

- KPI Cards: Total Employees, Promotions, Layoffs
- Bar Charts: Years of Service, Job Levels, Departmental Impact
- Donut Chart: Distance from Office
- Pie Chart: Overtime %
- Tables: Job roles with promotions & layoffs
- Employee Details: Promoted or Dismissed List

---

## 📈 Key Insights

- 👥 **Total Employees**: 1470  
- 🏆 **Promotion Candidates** (≥10 years no promotion): 72 (4.9%)  
- 🔥 **Layoff Candidates** (≥18 years): 117 (7.9%)  
- 🕐 **New Employees** (0–1 year): 44  
- 🚶 **Working Overtime**: ~30%  
- ✅ **High Performance Rating**: 84.6%  
- 😟 **Low Job Satisfaction**: 459 employees  
- 🧪 **Most affected department**: R&D  
- 💼 **Most common job role**: Sales Manager

---

## ✅ Recommendations

1. **Earlier Promotions**: Consider promoting employees before 10 years to boost morale.
2. **Performance-Based Layoffs**: Combine tenure and performance to determine layoffs.
3. **Training Programs**: Upskill level 1 and 2 employees to advance their roles.
4. **Satisfaction Review**: Conduct surveys/interviews for low-satisfaction employees.
5. **Remote/Flex Work Policy**: Consider alternatives for employees living far from office.

---

## 📎 Repository Files

- `HR_Analytics_Dashboard.pbix` – Power BI dashboard
- `README.md` – This report
- `Dataset/` – Original and cleaned dataset files


---

## 👤 Author

**Prashant Kumar**  
🎓 Final Year Computer Science Student  
💼 Data Analytics Enthusiast  


---

