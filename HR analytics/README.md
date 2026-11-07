# HR Analytics Dashboard (Power BI)
<img width="1171" height="657" alt="Screenshot 2026-11-07 191552" src="https://github.com/user-attachments/assets/a84ceb83-8b20-401a-9319-6ac9343e2592" />


A single-page Power BI dashboard analysing employee attrition across 1,470 employees, with KPIs, department, age, gender, education and job-satisfaction views and an education-level filter.

## KPIs
- Overall Employees: 1,470
- Total Attrition: 237
- Attrition Rate: 16.12%
- Active Employees: 1,233
- Average Age: 36.92

## Analysis
- **Employees by department:** workforce split across R&D, Sales and HR (pie chart)
- **Employees by age:** headcount by age band, split by gender (stacked column chart)
- **Job satisfaction rating:** count of employees by job role and satisfaction score (1 to 4), with conditional formatting (table)
- **Attrition by education field:** total attrition by field of study (bar chart)
- **Attrition by gender and age group:** gender split of attrition within each age band (five donut charts)
- **Education filter:** buttons to filter the whole page by education level (High School, Associate's, Bachelor's, Master's, Doctoral)

## Key insights from the dashboard
- 237 of 1,470 employees left, an attrition rate of 16.12%
- R&D is the largest department (65.37% of employees), followed by Sales (30.34%) and HR (4.29%)
- Most employees are aged 25 to 34 (554) or 35 to 44 (505)
- Life Sciences (89) and Medical (63) are the education fields with the highest attrition
- In every age group, males account for the larger share of attrition, from 52.63% (under 25) to 72.73% (above 55)
- Sales Executive (326), Research Scientist (292) and Laboratory Technician (259) are the largest job roles

## How it was built
- DAX measures for Overall Employees, Total Attrition, Attrition Rate and Active Employees
- Calculated columns for the age band and a numeric attrition value
- Conditional formatting on the job-satisfaction table and a slicer on education level

## Tech
Power BI, DAX, Data Modelling, Data Visualization

## Data
HR employee attrition dataset with 1,470 employee records: age, gender, department, job role, education, education field, job satisfaction and attrition status.

## How to open
Download `HR Analytics Dashboard.pbix` and open it in Power BI Desktop (free).
