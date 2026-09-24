# HR Analytics — Employee Attrition

## Project Overview

This project analyzes employee attrition using **Excel, SQL, Python, and Power BI**.

The goal is to understand employee turnover, identify workforce segments with higher observed attrition, and present the findings through an interactive HR dashboard.

**Workflow:**

`Excel → SQL → Python → Power BI`

---

## Business Problem

Employee attrition can increase recruitment costs, training requirements, workload, and productivity challenges.

This project investigates:

* Overall employee attrition
* Attrition by department
* Attrition by job role
* Attrition by age group
* Overtime and attrition
* Employee tenure
* Employee satisfaction
* Compensation and workforce characteristics

---

## Objectives

* Clean and prepare HR employee data
* Analyze employee attrition using SQL
* Perform exploratory data analysis with Python
* Build an interactive Power BI dashboard
* Identify important workforce patterns
* Provide data-driven business recommendations

---

## Dataset

The dataset contains **1,470 employee records** and includes information such as:

* Age
* Attrition
* Department
* Job Role
* Gender
* Monthly Income
* Job Level
* Overtime
* Job Satisfaction
* Work-Life Balance
* Total Working Years
* Years at Company
* Education
* Business Travel

### Key Statistics

| Metric           |  Value |
| ---------------- | -----: |
| Total Employees  |  1,470 |
| Employees Left   |    237 |
| Employees Stayed |  1,233 |
| Attrition Rate   | 16.12% |

---

## Tools & Technologies

* **Excel** — Data cleaning and preparation
* **MySQL** — SQL analysis
* **Python** — Exploratory Data Analysis
* **Pandas & NumPy** — Data manipulation
* **Matplotlib & Seaborn** — Data visualization
* **Power BI** — Interactive dashboard
* **DAX** — Business measures
* **Jupyter Notebook** — Python analysis environment

---

## Project Workflow

```text
Raw HR Data
     ↓
Excel Cleaning
     ↓
Cleaned Dataset
     ↓
MySQL Analysis
     ↓
Python EDA
     ↓
Power BI Dashboard
     ↓
Business Insights
```

---

## Data Cleaning

The data cleaning process included:

* Checking missing values
* Checking duplicate employee records
* Validating data types
* Standardizing categorical data
* Creating `Age_Group`
* Creating `Tenure_Group`
* Preparing the cleaned dataset for analysis

---

## SQL Analysis

MySQL was used to analyze:

* Total employees
* Employees who left and stayed
* Attrition rate
* Attrition by department
* Attrition by job role
* Attrition by overtime
* Attrition by age group
* Attrition by tenure
* Employee income and workforce metrics

---

## Python EDA

Python was used to explore employee and attrition patterns.

Key analysis included:

* Attrition distribution
* Department analysis
* Job role analysis
* Age group analysis
* Overtime analysis
* Tenure analysis
* Employee demographics

Visualizations were created using **Matplotlib and Seaborn**.

---

## Power BI Dashboard

The Power BI dashboard contains three main pages:

### 1. HR Overview

Provides an executive summary of:

* Total Employees
* Employees Left
* Employees Stayed
* Attrition Rate
* Average Age
* Average Monthly Income
* Average Years at Company

### 2. Attrition Analysis

Analyzes attrition by:

* Department
* Job Role
* Age Group
* Overtime
* Tenure

### 3. Employee Analysis

Provides an overview of:

* Gender
* Education
* Job Level
* Business Travel
* Income
* Department
* Years at Company

Interactive slicers allow users to filter the dashboard by **Department, Job Role, Gender, and Overtime**.

---

## Key Findings

* The overall observed attrition rate is **16.12%**.
* **237 of 1,470 employees** left the organization.
* Attrition varies across departments and job roles.
* Employees working overtime show substantially higher observed attrition in this dataset.
* Attrition patterns vary across age groups and tenure levels.
* Employee satisfaction, compensation, and work-life balance provide additional areas for investigation.

> These findings describe observed patterns in the dataset and do not establish causation.

---

## Business Recommendations

Based on the analysis, HR could:

* Investigate workload and overtime patterns.
* Review high-attrition job roles.
* Analyze early-tenure employee experiences.
* Monitor employee satisfaction and work-life balance.
* Examine compensation and career-development patterns.
* Use employee segmentation for more targeted retention analysis.

---

## Project Structure

```text
HR-Analytics-Employee-Attrition/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_insights.ipynb
│
├── sql/
│   └── 01_basic_analysis.sql
│
├── powerbi/
│   └── HR_Analytics_Dashboard.pbix
│
├── images/
│   ├── attrition_overview.png
│   ├── attrition_by_age_group.png
│   ├── attrition_by_department.png
│   ├── attrition_by_job_role.png
│   ├── attrition_by_overtime.png
│   ├── attrition_by_tenure.png
│   ├── dashboard.png
│   ├── attrition_analysis.png
│   └── employee_analysis.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

### Python

Install the required packages:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Run the notebooks in this order:

```text
01_data_cleaning.ipynb
02_eda.ipynb
03_insights.ipynb
```

### SQL

Open the SQL files in **MySQL Workbench** and run the analysis queries against the HR database.

## Power BI Dashboard

### HR Overview
<img width="1455" height="831" alt="HR_Overview" src="https://github.com/user-attachments/assets/f40ae258-3542-4435-83f4-2593a0e1c014" />

### Attrition Analysis
<img width="1457" height="837" alt="Attrition_Analysis" src="https://github.com/user-attachments/assets/2ccb0af6-471f-4bf7-8c8c-7a6986d47471" />

### Employee Analysis
<img width="1443" height="830" alt="Employee_Analysis" src="https://github.com/user-attachments/assets/a5d51505-ab8c-4d13-bd31-d017ba72efed" />

Refresh the data source if required, then explore the dashboard using the available filters and page navigation.
