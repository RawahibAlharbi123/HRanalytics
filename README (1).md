# HR Analytics Dashboard

An interactive Power BI dashboard analyzing employee distribution, demographics, and turnover across an organization. Built to help HR teams understand workforce composition and identify trends in attrition.

## 📊 Overview

This project explores employee data to answer key HR questions:
- How is the workforce distributed by gender, race, age, and location?
- What is the balance between headquarters and remote staff?
- How has headcount changed over time (2000–2020)?
- Which departments have the highest termination rates?

## 🗂️ Dataset

- **Source:** [Kaggle – HR Analytics dataset](https://www.kaggle.com/)
- **Format:** CSV files, cleaned and prepared in Excel before loading into Power BI
- Files included in this repository:

| File | Description |
|---|---|
| `DataSource(Human Resources).csv` | Main employee dataset |
| `age_group.csv` | Employee count by age group |
| `age_gender_group.csv` | Age group breakdown by gender |
| `gender.csv` | Overall gender distribution |
| `gender_department.csv` | Gender distribution by department |
| `race.csv` | Employee count by race |
| `location.csv` | Headquarters vs. remote distribution |
| `state.csv` | Employee count by U.S. state |
| `employee_change.csv` | Change in employee number (2000–2020) |
| `avg_tenure.csv` | Average tenure per employee |
| `avg_length_employment.csv` | Average length of employment (years) |
| `turnover_rate.csv` | Termination rate by department |
| `jobtitle.csv` | Employee count by job title |

## 🛠️ Tools Used

- **Excel** – data cleaning and preparation
- **SQL** – data querying and analysis
- **Power BI** – data modeling, DAX measures, and dashboard visualization

## 📈 Dashboard Pages

### 1. Employee Distribution Overview
- Gender distribution (Male, Female, Non-Conforming)
- Headquarters vs. Remote employees
- Change in employee number (2000–2020)
- Employees by state (map)
- Race distribution
- Average length of employment

### 2. Department & Demographics Breakdown
- Termination rate by department
- Age group distribution
- Gender distribution by department

## 🔑 Key Insights

- The workforce is close to gender-balanced, with slightly more male employees (8.9K) than female (8.1K).
- The majority of employees (about 75%) work from headquarters, while 25% work remotely.
- Average employee tenure is 8 years.
- Headcount has grown steadily since 2005, following a dip in the early 2000s.
- White employees make up the largest racial group (5.0K), followed by employees of two or more races and Black/African American employees (around 2.8K–2.9K each).
- The largest age group is 35–44 (5.1K), followed closely by 25–34 (4.9K) and 45–54 (4.8K).
- Auditing (0.20) and Legal (0.17) have the highest termination rates, while Marketing (0.11) has the lowest.
- Engineering is the largest department by far, with roughly 2.4K female and 2.7K male employees.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/RawahibAlharbi123/HRanalytics.git
   ```
2. Open `HR_dashboard.pbix` in Power BI Desktop.
3. Explore the interactive visuals and filters.

## 👤 Author

**Rawahib Alharbi**
Computer Science Graduate | Aspiring Data Analyst / BI Developer

---
*This project is part of a data analytics portfolio focused on HR and business intelligence use cases.*
