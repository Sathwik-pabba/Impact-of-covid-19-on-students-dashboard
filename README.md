# 👩‍💼 InnovateX HR Analytics Dashboard

## 📊 Project Overview

This project analyzes the InnovateX HR dataset to derive actionable insights, aiming to optimize HR operations, enhance employee satisfaction, and refine talent management strategies. By examining key HR metrics, the goal is to foster a positive work environment and drive organizational success.

---

## 🧩 Problem Statement

To analyze the InnovateX HR dataset and identify patterns in employee attrition, performance, compensation, and demographics. The objective is to uncover insights that can improve HR decision-making, boost employee retention, and develop effective talent management strategies that align with business goals.

---

## 📁 Dataset Description

-   **EmployeeNumber**: An identifier or unique number assigned to each employee.
-   **Age**: The age of an employee (in years).
-   **Attrition**: Categorical variable indicating if an employee has left ('Yes' / 'No').
-   **AttritionCount**: Numerical value for attrition count for a specific employee.
-   **BusinessTravel**: Frequency of business travel ('Travel Frequently', 'Travel Rarely', 'Non-Travel').
-   **Department**: The department where the employee works (e.g., 'Human Resources', 'Marketing', 'Information Technology').
-   **DistanceFromHome**: Distance between employee's home and workplace (in miles/kilometers).
-   **EducationField**: The field of study for the employee's highest education.
-   **Gender**: The gender of an employee ('Male' / 'Female').
-   **HourlyRate**: The rate at which an employee is paid per hour.
-   **JobRole**: The specific role or position the employee holds.
-   **JobSatisfactionRating**: Employee's satisfaction with their job (e.g., 1 to 5 scale).
-   **WorkLifeBalanceRating**: Employee's perceived balance between work and personal life (e.g., 1 to 5 scale).
-   **PerformanceRating**: An evaluation of an employee's performance (e.g., 1 to 5 scale).
-   **MaritalStatus**: Employee's marital status ('Married', 'Single', 'Divorced').
-   **MonthlyIncome**: The employee's monthly income or salary.
-   **OverTime**: Indicates if the employee works overtime ('Yes' / 'No').
-   **PercentSalaryHike**: The percentage increase in the employee's salary.
-   **YearsAtCompany**: The number of years an employee has worked at the company.
-   **YearsSinceLastPromotion**: The number of years since the employee's last promotion.

---

## 🛠️ Steps Followed

-   ✅ **Data Import**: Imported and cleaned the dataset.
-   🔍 **Data Cleaning**: Handled potential nulls, corrected data types, and renamed columns as needed.
-   📊 **KPI Cards**: Defined and calculated key performance indicators such as Total Attrition Count and Total Employees.
-   📈 **Segmented Analysis**: Performed detailed analysis of attrition rates by age groups, gender, and department.
-   📉 **Performance & Compensation Analysis**: Explored employee distribution by job role and performance rating, analyzed average hourly rates by department, and average monthly income by job role and gender.
-   🔗 **Relationship Analysis**: Investigated the correlation between attrition and percent salary hike.
-   ⭐ **Top N Analysis**: Identified the top 10 employees with the highest monthly income.
-   🎨 **Visualizations**: (If applicable, for Power BI dashboard) Utilized various charts like bar charts, donut charts for attrition rates, matrix for job role/performance, clustered column charts for income, and scatter plots for relationships.
-   📌 **Filtering**: (If applicable, for Power BI dashboard) Demonstrated how filters like "Marital Status" can dynamically change report page data for deeper insights.

---

## 💡 Key Insights

### Overall HR Metrics
* **Total Attrition Count**: 237
* **Total Employees**: 1470

### Attrition Analysis
* **Highest Attrition Age Group**: Employees **under 25**, particularly females (48.65% attrition rate), show the highest attrition.
* **Top Attrition Department**: The **Research & Development** department has the highest attrition count (133), indicating potential areas for concern within this area.
* **Attrition & Salary Hike**: There is a **very weak negative correlation** (-0.0135) between attrition and percent salary hike, suggesting that salary increases alone are not a strong determinant of retention. The average salary hike for those who left (15.10%) is very similar to those who stayed (15.23%).

### Compensation & Performance
* **Dominant Performance Rating**: A significant majority of employees across all job roles have a performance rating of **3**.
* **Similar Hourly Rates**: Average hourly rates are quite **consistent across all departments**, ranging from \$64.30 to \$66.17.
* **Highest Paying Roles**: **Manager** and **Research Director** are the job roles with the highest average monthly incomes.
* **Gender Income Disparity**: Generally, **males have slightly higher average monthly incomes** in most job roles compared to females.
* **Top Earners**: The top 10 highest-paid employees are predominantly **Managers** and **Research Directors**.

---

## ✅ Recommendations

1.  **Prioritize Youth Retention Programs**: Implement targeted mentorship programs, clear career progression paths, and engagement initiatives specifically for employees under 25 to address their high attrition rates.
2.  **Deep Dive into R&D Department**: Conduct a thorough investigation into the 'Research & Development' department to identify root causes of high attrition. This might involve reviewing workload, management practices, career development opportunities, and work-life balance.
3.  **Implement Holistic Retention Strategies**: Focus on non-monetary factors like work-life balance, job satisfaction, employee recognition, professional development, and a positive work culture, as salary hikes alone are not significantly impacting attrition.
4.  **Ensure Pay Equity**: Regularly audit and adjust salary structures to ensure fairness and reduce gender-based income disparities across all job roles.
5.  **Leverage Marital Status Filter**: Utilize `Marital Status` as an interactive filter in HR dashboards (e.g., in Power BI) to analyze specific trends (e.g., attrition, job satisfaction) within different marital groups, allowing for more tailored HR interventions.

---

## 📁 Files Included

* `InnovateX HR Dataset.pbix` – (Your Power BI dashboard file, if created)
* `InnovateX_HR_Dashboard_Preview.png` – (A screenshot of your dashboard, if created)
* `InnovateX+HR+Data_set (1).xlsx` – The original dataset file.

---

## 🙋‍♂️ About Me

I'm a data analyst with expertise in **Power BI**, **SQL**, and **Python**, passionate about turning raw data into clear business insights.
Check out more on my [GitHub Profile](https://github.com/Sathwik-pabba).

---

## 🔗 Connect with Me

* 💼 [LinkedIn](https://linkedin.com/in/sathwikpabba)
* 📫 Email: sathwik.pabba18@email.com
