# 📊 Salaries in 2025 - Data Analytics Project

This project analyzes expected salary trends in 2025 using a survey-based dataset. The goal is to extract insights on roles, companies, work types, and countries offering the best salaries and opportunities, using Python for data cleaning and Power BI for interactive dashboards.

---

## 🛠️ Tools Used

- **Python** (Pandas, NumPy)
- **Power BI**
- **Excel**
- **Git & GitHub**

---

## 🧹 Data Cleaning Process

The raw dataset contained multiple issues and inconsistencies. Key cleaning steps included:

- **Salary & Years of Experience:**
  - Standardized formats and converted to numeric types.

- **Title Column Enhancements:**
  - Extracted meaningful information to create:
    - `General Role`
    - `Skills`

- **Experience Level:**
  - Derived `Experience Level` column based on cleaned experience years.

- **Location Mapping:**
  - Created a `Country` column by mapping from `City of Company Site`.

- **Text Fixes:**
  - Fixed typos, whitespace issues, and inconsistent formatting.

> ✅ Cleaned data saved as `salary(cleaned).csv`  
> ✅ Cleaning script in `data_cleaning.py`

---

## 📊 Dashboards Overview

### 1. `country_site_dash`
- Visualizes **salary distribution by country**.
- Highlights the **top-paying companies**.
- Shows company-level salaries across different **work types**.

### 2. `general_role_dash1`
- Identifies the **highest-paid roles**.
- Analyzes each role in terms of:
  - **Company**
  - **Work Type**
  - **Work Hour**
  - **Country**

### 3. `general_role_dash2`
- Displays:
  - Most **common roles**
  - Associated **experience levels**
  - **Salary distribution** per role and experience level

### 4. `experience_level_dash`
- Explores:
  - Distribution of experience levels
  - Salary trends per level
  - Company-level salary distribution by experience level

> All dashboards are in the Power BI file: `dashboard.pbix`

---

## 🔍 Key Insights

- **Most common role:** Software Engineer  
- **Highest total salary:** Software Engineer (6M EGP)  
- **Highest paid role overall:** CTO (213,826 EGP)  
- **Most in-demand experience level:** Entry Level  
- **Top-paying experience levels:** Lead & Management  
- **Best role (demand + salary):** Software Engineer  
- **Top-paying work types:**
  - **Hybrid:** 34,500 EGP
  - **Full-time:** 30,000 EGP
- **Top-paying skill:** Microsoft Dynamics CRM (433,950 EGP)  
- **Top-paying country:** Switzerland (225,080 EGP)  
- **Top-paying company:** Corporate (60,000 EGP)  
- **Overall average salary:** 39,950 EGP  
- **Egyptian companies** offer higher salaries for Internal Auditor roles  
- **Salaries drop** significantly in lower-technical roles  
- **Non-Egyptian countries** dominate top salary positions  
- **Part-time roles** can offer surprisingly higher average salaries  

---

## 🖼️ Sample Dashboards

### 🌍 Country & Company Insights
![Country Dashboard](country_site_dash.png)

### 💼 Roles vs Companies
![Role Dashboard 1](general_role_dash1.png)

### 🧠 Roles & Experience Levels
![Role Dashboard 2](general_role_dash2.png)

### 📈 Experience Level Analysis
![Experience Dashboard](experience_level_dash.png)

---

## 📁 Project Structure

Salaries_in_2025/
│
├── data/
│ └── salary(cleaned).csv
│
├── scripts/
│ └── data_cleaning.py
│
├── dashboards/
│ └── dashboard.pbix
│
├── images/
│ ├── country_site_dash.png
│ ├── general_role_dash1.png
│ ├── general_role_dash2.png
│ └── experience_level_dash.png
│
└── README.md

