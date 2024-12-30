# HR Analytics: Absenteeism Analysis and Dashboard
## Project Overview
This repository showcases a comprehensive data analysis project aimed at creating a robust HR dashboard to reward healthy employee behavior while providing insights into absenteeism patterns. The project combines SQL, data visualization with Power BI, and advanced data analysis techniques to deliver actionable insights for HR teams.
## Project Objectives
1. **Reward Healthy Employees**: Identify employees with low absenteeism for a $1,000 bonus program.
2. **Compensation Adjustment**: Calculate wage increases for non-smokers within a defined budget.
3. **Dashboard Insights**: Develop an interactive HR dashboard to analyze absenteeism patterns across multiple dimensions.
## Tools and Techniques
- **SQL**: Data preprocessing, transformations, and subquery optimization.
- **Power BI**: Interactive dashboard creation with advanced visualizations.
- **Data Analysis**: Categorizing employee behavior using metrics such as BMI, smoking habits, and absenteeism.
## Workflow
### 1. Database Setup
A structured SQL database named `work` was created in SQL Server Studio, incorporating:
- Absenteeism Data ([Absenteeism_at_work.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Absenteeism_at_work.csv))
- Reasons for Absence ([Reasons.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Reasons.csv))
- Compensation Data ([Compensation.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/compensation.csv))

SQL queries joined and optimized tables for efficient data import into Power BI.
### 2. Key Calculations and Metrics
- **Main KPIs**:
  - Average absenteeism (7.19 hours).
  - Employee count and total absentee hours.
- **Secondary Metrics**:
  - Absentee patterns categorized by education, pets, children, and BMI.
- **Calculated Fields**:
  - Distribution of bonus among healthy employees.
  - Wage increases for non-smokers.
  - Seasonal trends in absenteeism.
### 3. SQL Queries
Efficient SQL queries enabled:
- Joining datasets with `LEFT JOIN` and subqueries.
- Categorizing employees based on BMI, smoking habits, and absenteeism.
- Filtering data for visualization-ready output.
  
File: [HR Analytics.sql](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analtyics.sql)
### 4. Wireframe and Design
The dashboard's layout aligns with the provided wireframe:

- **Sections**:
  - Main KPIs and narratives.
  - Supporting metrics with pie charts and distributions.
  - Monthly and weekly absenteeism trends.
  - Detailed tables and scatter plots for comparison.
- **Design Elements**:
  - Professional dark theme with icons for clarity.
  - Interactive filters for real-time updates.
  - Export-ready format for stakeholder presentations.
    
File: [Wireframe.png](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Wireframe.png)
### 5. Power BI Dashboard
An interactive dashboard, adhering to the wireframe design, was developed with features including:

- **Main KPIs**:
  - Average absenteeism time in hours.
  - Total employee count and absentee hours.
- **Trend Analysis**:
  - Monthly absentee patterns.
  - Day-of-week absentee trends.
- **Detailed Visualizations**:
  - Pie charts for demographic insights.
  - Scatter plots for correlations (e.g., transportation expense vs. workload).
    
File: [HR Analytics Dashboard.pbix](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analytics%20Dashboard.pbix)
## Final Dashboard Features
- **Interactive Visualizations**:
  - Absenteeism trends by seasons and weekdays.
  - Employee distributions by education, pets, children, and BMI.
- **HR Insights**:
  - Reasons for absenteeism categorized for analysis.
  - Correlation between workload and transportation expenses.
- **Customization**:
  - Dynamic narratives for stakeholder engagement.
  - Placeholder areas for additional metrics.

![dashboard image](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analytics%20Dashboard.png)

File: [HR Analytics Dashboard.pbix](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analytics%20Dashboard.pbix)
## Repository Contents
- [Absenteeism_at_work.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Absenteeism_at_work.csv): Raw absenteeism data.
- [Reasons.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Reasons.csv): Reasons for absenteeism.
- [Compensation.csv](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/compensation.csv): Employee compensation data.
- [HR Analytics.sql](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analtyics.sql): SQL scripts for data preparation.
- [HR Analytics Dashboard.pbix](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analytics%20Dashboard.pbix): Power BI dashboard file.
- [HR Analytics Dashboard.png](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/HR%20Analytics%20Dashboard.png): Screenshot of the dashboard.
- [Wireframe.png](https://github.com/ndomah/HR-Analytics-Absenteeism-Analysis-and-Dashboard/blob/main/Wireframe.png): Dashboard wireframe design.
## Conclusion
This project exemplifies the integration of SQL and Power BI for data-driven decision-making. It provides HR teams with actionable insights to improve employee engagement, reward healthy behavior, and optimize absenteeism policies.
