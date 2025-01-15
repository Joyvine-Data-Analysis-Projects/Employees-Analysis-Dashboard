# Employees-Analysis-Dashboard
# Overview
This dataset contains information about employees, including their demographic details, job-related data, and compensation. It is designed for HR analytics, workforce planning, 
and organizational insights. The dataset includes fields such as employee ID, job title, department, salary, and attrition data.

# Dataset Structure
The dataset comprises the following columns:

**EEID**

Unique identifier for each employee.

**Job Title**

Employee's job title within the organization.

**Department**

The department to which the employee belongs.

**Business Unit**

The business unit or division the employee is associated with.

**Gender**

Gender of the employee.

**Ethnicity**

Ethnic background of the employee.

**Age**

Employee's age.

**Hire Date**

Date when the employee was hired.

**Annual Salary**

Annual base salary of the employee in USD.

**Bonus**

Bonus percentage of the annual salary.

**Country**

Country where the employee is located.

**City**
City where the employee is located.

**Exit Date**

Date when the employee exited the organization (if applicable).

## Key Calculations

 Derived Metrics

**Real Bonus Amount**

 - Annual Salary * (Bonus % / 100)
 
 - Calculates the monetary value of the bonus based on the percentage provided.

**Tenure**
 - DATEDIF(Hire Date, Exit Date or TODAY(), "Y")
 Calculates the total years of service for each employee.

**Age Grouping**
 - Categories
 - <30
 - 30-40
 - 40-50
 - >50
 - IF(Age<30, "<30", IF(Age<=40, "30-40", IF(Age<=50, "40-50", ">50")))

## Visualisations and Insights

- Bar charts showing average salaries across different departments, job title and business units to help in finacial analysis.
- Pie chart showing distribution of employees by gender.
- Doughnut chart showing distribution on employees across diffferent ethnicity.
- Bar charts showing distribution of employees across different age groups, departments and countries.
- KPIs to track performance and statistics to help in decision making.

## Tools Used
- MS Excel 2016 for cleaning data, building visualizations and consolidating into a dashboard for easy reveiwing.

## Future Enhancements
- Integrate with Power BI for advanced visualization.
- Add performance ratings and promotion history.
- Prepare a Report.
