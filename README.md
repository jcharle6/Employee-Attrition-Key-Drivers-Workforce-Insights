# employee-attrition-analysis
HR analytics project analyzing employee attrition patterns using Excel pivot tables, conditional logic, and Tableau dashboards to identify key drivers of workforce turnover.

# Employee Attrition Analysis

## Overview

This project is an HR analytics study focused on understanding employee attrition patterns within an organization.

Using Excel and Tableau, the analysis explores how factors such as department, job role, overtime, and income levels impact employee turnover.

The dataset contains **1,470 employees**, with the goal of identifying key drivers behind attrition and high-risk employee segments.

A Tableau dashboard was built to visualize attrition trends and support interactive exploration of workforce data.

---

## Business Problem

Employee retention is critical for maintaining productivity and reducing hiring costs. High attrition can indicate issues related to compensation, workload, job satisfaction, or organizational structure.

This project investigates:

* Overall attrition rate within the organization
* Departments and job roles most affected by attrition
* Impact of overtime on employee turnover
* Relationship between income levels and attrition risk
* Visual patterns in attrition using Tableau dashboards

---

## Tools & Technologies

* **Excel** — Data cleaning, pivot tables, and conditional logic  
* **Tableau** — Interactive dashboards and visual analytics  
* **IF Statements** — Creation of attrition flag  
* **Pivot Tables** — Aggregation and exploratory analysis  
* **HR Analytics Techniques** — Workforce segmentation and trend analysis  

---

## Data Cleaning & Preparation

The dataset was cleaned and structured for analysis:

* Standardized column formatting across all variables  
* Removed inconsistencies and ensured data accuracy  
* Created a binary **Attrition Flag** using conditional logic  
* Organized categorical variables for pivot table analysis  
* Validated employee counts across all segments  

---

## Key Metrics

* Total Employees: **1,470**
* Attrition Count: **237**
* Attrition Rate: **16.12%**
* Active Employees: **1,233**
* Average Monthly Income: **$6,502.93**
* Average Job Satisfaction: **2.73**

---

## Exploratory Data Analysis

### Department-Level Attrition

| Department              | Attrition Rate |
| ----------------------- | -------------- |
| Human Resources         | 19.05%         |
| Research & Development  | 13.84%         |
| Sales                   | 20.63%         |

**Key Insight:** Sales and Human Resources experience higher attrition compared to Research & Development.

---

### Overtime vs Attrition

| Overtime | Attrition Rate |
| -------- | -------------- |
| No       | 10.44%         |
| Yes      | 30.53%         |

**Key Insight:** Employees working overtime are significantly more likely to leave the company.

---

### Job Role Analysis

| Job Role                  | Attrition Rate |
| ------------------------- | -------------- |
| Sales Representative      | 39.76%         |
| Laboratory Technician     | 23.94%         |
| Human Resources           | 23.08%         |
| Manager                   | 4.90%          |
| Research Director         | 2.50%          |

**Key Insight:** Lower-level and sales-related roles experience significantly higher attrition rates.

---

### Income Level Analysis

| Monthly Income Range | Attrition Rate |
| -------------------- | -------------- |
| 1000–3999            | 25.28%         |
| 4000–6999            | 10.75%         |
| 7000–9999            | 14.29%         |
| 13000–15999          | 6.78%          |
| 16000–18999          | 1.32%          |

**Key Insight:** Lower income groups show significantly higher attrition rates compared to higher earners.

---

## Tableau Dashboard

An interactive Tableau dashboard was created to visualize attrition patterns across departments, job roles, overtime status, and income levels.

The dashboard allows users to:
- Explore attrition trends dynamically
- Filter by department, job role, and other categories 
- Identify high-risk employee segments visually  

🔗 Tableau Public Dashboard: [here](https://public.tableau.com/app/profile/justin.hilaire/viz/EmployeeRetentionAnalytics_17781151671300/Dashboard1)

---

## Key Findings

* Overall attrition rate is **16.12%**
* Overtime is the strongest driver of attrition (30%+ rate)
* Sales and HR departments show higher turnover risk
* Sales Representative role has the highest attrition rate (39.76%)
* Lower income strongly correlates with higher attrition
* Senior roles have significantly stronger retention

---

## Conclusion

This analysis highlights clear patterns in employee turnover:

* Workload (overtime) significantly impacts attrition  
* Compensation level is strongly linked to retention  
* Certain departments and job roles are higher risk areas  
* Tableau visualization strengthens pattern recognition and communication of insights  

These insights can help guide HR strategies around workload distribution, compensation review, and employee retention planning.

---

<img width="1249" height="999" alt="Dashboard 1 (7)" src="https://github.com/user-attachments/assets/31f15a7a-224a-4c9a-b104-778339130fae" />


