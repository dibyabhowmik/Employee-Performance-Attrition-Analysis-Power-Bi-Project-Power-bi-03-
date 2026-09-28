Project Overview:
This project presents an Employee Performance & Attrition Analysis dashboard developed in Microsoft Power BI to analyze employee performance, salary trends, workforce distribution, and employee attrition.
The project integrates multiple datasets related to employees, departments, salaries, and performance reviews into a structured data model. The dashboard provides an interactive view of key HR metrics and enables users to analyze employee trends across different years and departments.

The analysis focuses on answering important business questions such as:
How many employees are currently represented in the dataset?
What is the overall attrition/exit level?
How is the workforce distributed across departments?
Which departments experience higher employee attrition?
How have salaries changed over time?
How does employee performance vary?
Who are the top-performing employees?
How does annual attrition change over time?
Project Objectives:
The main objectives of this project were to:

Analyze employee attrition across different years and departments.
Evaluate employee performance using performance review scores.
Analyze salary trends over time using minimum, average, and maximum salary values.
Understand workforce distribution across departments.
Identify top-performing employees within the organization.
Create an interactive HR analytics dashboard for easier exploration of employee data.
Build a structured relational data model connecting employee, department, salary, and performance information.
Present HR insights through meaningful KPIs and visualizations to support data-driven decision-making.
Dataset:

The project uses multiple Excel-based datasets:
Dataset	Description
employees	Contains employee-level information such as Employee ID, department, joining year, exit year, attrition status, and employee exit information.
departments	Department master table containing department IDs and department names.
salaries	Contains employee salary information, salary amounts, and effective dates.
performance_reviews	Contains employee performance review records, review dates, reviewers, and performance scores.
Salary Trend	Prepared dataset used for analyzing salary movement across years.
Salary Trends Over Time	Supporting salary trend dataset used for time-based salary analysis.
Top performers per dept	Prepared dataset used to identify high-performing employees by department.
Attrition Rate per Year	Prepared dataset used for annual attrition-rate analysis.

The project also includes an ER/Data Model diagram showing the relationships between the major tables.

Tools & Technologies:
SQl- For Data query 
Microsoft Power BI – Dashboard development and data visualization
Power Query – Data cleaning and transformation
DAX – Measures and analytical calculations
Microsoft Excel – Source datasets and supporting analysis
Data Modeling – Relationships between multiple HR datasets

Data Analysis & Preparation Process:
1. Data Collection:
The project began with multiple Excel datasets covering:
Employee information
Department information
Salary records
Performance reviews
Attrition information
Supporting analytical tables
2. Data Cleaning & Transformation:
The datasets were prepared before creating the dashboard. The preparation process involved:
Checking the structure and consistency of the datasets.
Ensuring appropriate data types for dates, numerical values, and categorical fields.
Preparing year-based fields such as Join Year, Exit Year, and Salary Year.
Organizing department information using a separate department reference table.
Preparing salary and performance data for analytical reporting.
Creating supporting datasets for salary trends, annual attrition, and top performers.
3. Data Modeling:
A relational data model was created in Power BI to connect the different datasets.

The major tables include:

Employees → Departments
Employee department information is connected to the department master table.

Employees → Salaries
Employee salary records are associated with individual employees.

Employees → Performance Reviews
Employee performance review records are linked using Employee ID.

Supporting tables such as salary trends and top-performer datasets were also connected to the dashboard model where required.

This structure allowed information from different datasets to be analyzed together through common dimensions such as Employee ID, Department, and Year.

This model provides a foundation for analyzing employee performance, salaries, departments, and attrition within a single Power BI report.

Dashboard Overview:

The dashboard is titled Employee Performance & Attrition Analysis and contains several interactive sections.
KPI Cards

The dashboard provides three major KPI cards:

Average Performance Score: 7.53
Total Attrition Count: 16
Total Employees: 30

These KPIs provide a quick overview of the overall workforce and performance situation.

Employee Distribution by Department

A donut chart shows how the 30 employees are distributed across departments.

The dashboard displays:

Engineering – 10 employees
HR – 9 employees
Sales – 6 employees
Finance – 5 employees

This visualization provides a quick understanding of the workforce composition across departments.

 Attrition Count by Department

The dashboard also analyzes employee attrition by department.

The displayed attrition counts are:

HR – 5
Sales – 5
Engineering – 3
Finance – 3

This allows HR teams to identify departments where employee exits are more concentrated.

 Salary Trend Analysis

The Salary Trend visualization tracks three salary measures over time:

Minimum Salary
Average Salary
Maximum Salary

The visualization helps identify changes in salary levels across different salary years.

The dashboard also provides a Salary Year slicer, allowing users to focus on particular years.

 Annual Attrition Rate & Employee Exits

The dashboard combines:

Annual Attrition Rate (%)
Number of Employees Left

in a time-based visualization.

This allows users to examine how employee exits and attrition rates changed over the years rather than looking only at the overall attrition figure.

 Top Performers

The Top Performers section displays employees with higher average performance scores.

The dashboard currently highlights employees including:

Ivan
Hannah
Judy
Bob

The visualization also uses department information to distinguish employees across different departments.

Interactive Filters

The dashboard includes multiple slicers that allow users to dynamically explore the data.

Join Year

Users can filter employees based on their joining year.

Exit Year

Users can analyze employee exits based on the year they left the organization.

Salary Year

Users can examine salary trends for individual years.

Department Name

Users can filter the analysis by:

Engineering
Finance
HR
Sales

These filters allow the dashboard to be used for both overall HR analysis and department-specific analysis.

Key Insights
1. Overall Workforce

The dashboard contains 30 employees and records 16 employee exits/attritions.

This provides a high-level view of workforce movement within the dataset.

2. Department Distribution

Engineering represents the largest employee group with 10 employees, followed by HR with 9, Sales with 6, and Finance with 5.

This indicates that the workforce is not evenly distributed across departments.

3. Department-Level Attrition

HR and Sales each account for 5 recorded attritions, while Engineering and Finance each account for 3.

Therefore, employee exits are distributed differently from the overall workforce size, making department-level analysis important when investigating attrition.

4. Employee Performance

The overall average performance score is 7.53, providing a benchmark for evaluating employee performance within the dataset.

The Top Performers visualization further enables identification of employees with comparatively higher performance scores.

5. Salary Movement

The salary trend analysis shows changes in minimum, average, and maximum salary levels over time.

Analyzing these three measures together provides a broader view of salary progression rather than relying only on average salary.

6. Attrition Over Time

The annual attrition visualization combines the attrition rate with employee exits, making it possible to identify years where employee turnover was relatively higher or lower.

7. Multi-Dimensional Analysis

By combining department, joining year, exit year, salary year, performance score, and salary information, the dashboard enables users to move beyond basic employee counts and investigate workforce patterns from multiple perspectives.


HR Insights & Business Interpretation
