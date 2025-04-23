# 🧑‍💼 Human Resources Analytics Dashboard

A comprehensive HR dashboard designed for workforce analysis and operational insights. This project simulates a real-world HR data environment with over **8,950 employees**, offering **executive-level summaries**, **demographic analysis**, **salary breakdowns**, and **detailed employee records**.

---

## 📌 Project Objective

**As an HR Manager**, the goal is to:
- Monitor company-wide HR metrics in real-time.
- Track hiring, attrition, and departmental distributions.
- Understand gender, age, education, and salary dynamics.
- Identify trends that support data-driven HR decisions.

---

## 📊 Dashboard Overview

### 🔹 Summary View

#### ✅ Overview Section
- **Total Hired**: 8,950 | **Terminated**: 966 | **Active**: 7,984  
- **Department Breakdown**: Operations, Sales, Customer Service, etc.
- **Hired vs Terminated Trend Lines**
- **Headquarters vs Branch Comparisons**
- **Employee Map by State & City**

#### 🔹 Demographics
- **Gender Ratio**: 54% Male, 46% Female
- **Education vs Age Clusters**
- **Performance vs Education Matrix**

#### 🔹 Income Analysis
- **Salary vs Education & Gender**
- **Age-Salary Correlation by Role**
- **Outliers like Finance & IT Managers identified via scatter plot**

---

### 📋 Employee Records View

A detailed table with filters on:
- **ID, Name, Gender, Education**
- **Job Title, Department**
- **Salary, City, State**
- **Hire/Termination Dates**
- **Years at Company**

This allows for in-depth HR audits and employee-level analytics.

---

## 🧪 Data Generation Process

The dataset was synthetically generated using Python (`Faker`, `NumPy`, `Pandas`) with HR logic and realistic constraints. Below is an outline:

### 📍 Attributes Included
- Employee ID, Name, Gender, Location
- Department & Role (with weighted probabilities)
- Education Level (mapped per job title)
- Hire Date & Termination Date (with constraints)
- Age (based on role & education)
- Salary (adjusted based on gender, education, age)
- Performance Rating
- Overtime Status

### 📘 Custom Logic Implemented
- **Weighted hiring distribution (2015–2024)**
- **11.2% termination rate with timing logic**
- **Education-gender salary multipliers** (e.g., Female PhDs get +17%)
- **Age-based salary scaling (0.1%–0.3% yearly increase)**
- **Headquarters: New York; Branches: various US states**

  Tableau public link - https://public.tableau.com/app/profile/dhuwaraha.radhakrishnan/viz/HumanResourceAnalyticsDashboard_17430652062890/HRSummary
  
