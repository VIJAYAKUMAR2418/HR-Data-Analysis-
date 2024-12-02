# HR-Data-Analysis-

## Objective

- Composition of the Workforce:
 Understand the composition of the workforce by department, education field, business travel frequency, gender, job role, and age group.
- HR KPI:
 Analyze employee count, average salary, average monthly salary, average age, average salary hike, average Job satisfaction score, and gender ratio.
Identify trends and patterns in employee data across different parameters like Education, Age group, and Department.
Analyze different HR KPIs for different Job roles.
Show the impact of Age & Department on Salary.
- Employee Attrition Analysis:
 Identify the factors that influence employee turnover and retention, such as salary, age, gender, education, and employee demographics (e.g., age, marital status, work-life balance).
Gain insights into areas with high attrition rates to inform targeted retention strategies.
Analyze the attrition rate by various parameters including business travel, job satisfaction, marital status, work-life balance, monthly income, and age.
Compare the attrition rates in different departments such as Sales, R&D, and HR.

##DAX Measures for HR Dashboard

-Measure to Calculate Attrition Count

Attrition Count = CALCULATE([Employee Count], HR_Analytics[Attrition]="Yes")

-Measures to Calculate Attrition Rate

DIVIDE ([Attrition Count],CALCULATE ( [Employee Count], ALL ( HR_Analytics[Attrition] ) ),0)

## Insights 

- The employee attrition rate is 16%, which is higher than the industry average of 12%. The main reasons for attrition are low salaries, high workload, and lack of career growth opportunities.
-The employee diversity and inclusion analysis reveals that there is a significant gap in gender representation, especially in HR, where only 33% are female. The education field is also dominated by Life Sciences & Medical, which accounts for more than 50% of the employees.
- The total employee count is 1233 with an average salary of $6,879 and a monthly total payroll of $8.5M.
- The majority of employees are in the age group of 26-35 (490) and 36-45 (425).
Sales Executives are the largest job role (269), followed by Research Scientists (245).
-The highest average salaries are drawn by Managers ($17,201) and Research Directors ($15,947).
- Gender ratio is skewed towards one gender at 68%.
- The total attrition count is 237 with an overall attrition rate of 16%.
- Attrition rates vary across departments, with Sales (21%), R&D (19%), and HR (14%) having the highest rates.
- Among job roles, Sales Representatives (40%), Laboratory Technicians (24%), and Human Resources Specialists (23%) have the highest attrition rates.
- Employees who travel frequently for business have a higher attrition rate (25%) compared to those who rarely travel (8%).
- Employees who are dissatisfied with their jobs have a higher attrition rate (23%) compared to those who are satisfied (11%).
- The average age of employees facing attrition is 34.
- Attrition rates vary significantly based on job satisfaction levels; employees with lower job satisfaction have higher attrition rates.
Single employees face a higher rate of attrition compared to married or divorced employees.
