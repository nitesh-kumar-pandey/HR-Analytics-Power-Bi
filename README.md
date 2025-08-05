# Project Documentation: HR Analytics Dashboard
## 1. Project Overview
  This Power BI project provides a comprehensive HR Analytics Dashboard designed to analyze and visualize employee attrition trends, identify contributing factors, and      support data-driven decision-making.
  The dashboard consolidates HR data to track workforce metrics such as attrition rate, demographics, education background, job satisfaction, and salary-related factors.
________________________________________
## 2. Objectives
&emsp;  •	To monitor overall employee attrition and its distribution.<br>
&emsp;  •	To identify patterns and key reasons for attrition across different segments (age, education, salary, job role, etc.).<br>
&emsp;  •	To enable HR teams to make informed decisions for retention strategies.<br>
&emsp;  •	To create an interactive and visually intuitive dashboard for quick insights.<br>
________________________________________
## 3. Data Sources<br>
&emsp;  •	Primary Data Source: HR employee records (Excel/CSV/Database).<br>
&emsp;  •	Key Data Fields:<br>
&emsp;  &emsp;  ➢	Employee ID<br>
&emsp;  &emsp;  ➢	Age<br>
&emsp;  &emsp;  ➢	Gender<br>
&emsp;  &emsp;  ➢	Education Field<br>
&emsp;  &emsp;  ➢	Salary Slab<br>
&emsp;  &emsp;  ➢	Job Role<br>
&emsp;  &emsp;  ➢	Years at Company<br>
&emsp;  &emsp;  ➢	Job Satisfaction (1-4 scale)<br>
&emsp;  &emsp;  ➢	Attrition (Yes/No)<br>
________________________________________
## 4. Key Metrics and KPIs<br>
&emsp;  •	Count of Employees: Total number of employees in the dataset.<br>
&emsp;  •	Attrition Count: Number of employees who have left.<br>
 &emsp; •	Attrition Rate (%):<br>
&emsp;     &emsp;     &emsp;     &emsp;     &emsp;    Attrition Rate= (Attrition Count / Total Employees) ×100<br>
&emsp;  •	Average Age: Mean age of employees.<br>
&emsp;  •	Average Salary: Mean salary.<br>
&emsp;  •	Average Years: Average tenure in years.<br>
________________________________________
## 5. Dashboard Components<br>
&emsp;  a) Summary Cards<br>
&emsp; &emsp;   •	Count of Employees<br>
&emsp; &emsp;  •	Attrition Count<br>
&emsp; &emsp;   •	Attrition Rate<br>
&emsp;  &emsp; •	Average Age<br>
&emsp; &emsp;  •	Average Salary<br>
&emsp; &emsp;  •	Average Years at Company<br>
&emsp; b) Attrition by Education<br>
&emsp;&emsp;    •	Donut chart showing attrition distribution across education fields (Life Sciences, Medical, Marketing, etc.).<br>
&emsp;  c) Attrition by Age<br>
&emsp;&emsp;    •	Bar chart categorizing attrition by age groups (18–25, 26–35, 36–45, etc.).<br>
&emsp;  d) Attrition by Gender<br>
&emsp;&emsp;    •	Stacked bar chart comparing attrition between male and female employees.<br>
&emsp;  e) Attrition by Salary Slab<br>
&emsp;&emsp;    •	Horizontal bar chart showing attrition counts across salary categories (e.g., Up to 5k, 5k–10k, etc.).<br>
&emsp;&emsp;  f) Attrition by Years at Company<br>
&emsp;&emsp; &emsp;&emsp;   •	Line chart showing attrition trends against employee tenure.<br>
&emsp;&emsp;  g) Job Satisfaction vs Job Role<br>
&emsp;&emsp;  &emsp;&emsp;  •	Matrix visual displaying job satisfaction scores (1–4) for each job role.<br>
&emsp;&emsp;  h) Attrition by Job Role<br>
&emsp;&emsp; &emsp;&emsp;   •	Horizontal bar chart showing attrition count per job role.<br>
________________________________________
## 6. Interactivity<br>
&emsp;  •	Filters/Slicers:<br>
&emsp;   &emsp; ➢	Department selection (Human Resource, Research & Development, Sales)<br>
&emsp;   &emsp; ➢	Drill-down capability for more detailed analysis.<br>
________________________________________
## 7. Tools & Technologies Used<br>
&emsp;  •	Power BI Desktop: For data modeling, visualization, and dashboard creation.<br>
&emsp; •	DAX (Data Analysis Expressions): For calculated columns and measures.<br>
&emsp;  •	Power Query: For data cleaning and transformation.<br>
________________________________________
## 8. Insights and Observations<br>
&emsp;  •	Highest attrition is seen in the 26–35 age group.<br>
&emsp;  •	Employees with Life Sciences education have the highest attrition percentage.<br>
&emsp;  •	Lower salary slabs (up to 5k) show significantly higher attrition.<br>
&emsp;  •	Certain job roles (Laboratory Technician, Sales Executive) experience the most attrition.<br>
________________________________________
## 9. Future Enhancements<br>
&emsp;  •	Integration with real-time HR databases.<br>
&emsp;  •	Predictive modeling for attrition risk.<br>
&emsp;  •	Adding more demographic dimensions (location, marital status, etc.).<br>
&emsp;  •	Exportable automated HR reports.<br>
