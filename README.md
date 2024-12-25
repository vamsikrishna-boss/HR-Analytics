# Project : HR Analytics 
## Interduction
The HR Analytics Dashboard provides an interactive and detailed analysis of employee data, focusing on employee count, attrition trends, and other HR metrics. This dashboard is built using Tableau and is designed to help HR teams monitor workforce dynamics effectively.

## Key Objectives
1.  Identify total employee count and active employees.
2.  Analyze employee attrition by various dimensions such as gender, department, and age group.
3.  Understand job satisfaction levels across roles.
4.  Visualize education field-wise and gender-specific attrition trends.

## Dashboard Features:

1. Employee Count
Displays the total number of employees in the organization.

        (How to Create: Use a simple aggregated count of employee IDs.)

2. Attrition Count
Attrition represents the number of employees who left the company.

        (How to Create: Calculate attrition count using a filter on employee exit status.)

3. Handling Zero or Null Values:
Replace zeros with percentages for better data visualization.

        Steps:
        Go to the Values drop-down.
        Select Format.
        Click the drop-down and choose Percentage.
   
4. Active Employees
Displays the number of employees currently working in the organization.

        Calculation: Subtract attrition count from total employee count.
   
5. Attrition by Gender
Highlights the gender distribution of employees leaving the company.

        Visualization: Use a bar chart or pie chart to represent male and female attrition counts.
   
6. Synchronizing Axis
Combine multiple chart types (e.g., bar and circle) for enhanced visualization.

         Steps:
         Add both measures to a dual-axis chart.
         Right-click on the axis and select Synchronize Axis.
   
7. Adjusting Label Alignment
Labels can be adjusted for clarity.

         Steps:
         Select the Labels option.
         Click Automatic and choose Center, Left, or Right.
    
8. Department-wise Attrition
Visualizes attrition rates across departments (e.g., HR, R&D, Sales).

         Visualization: Use a pie chart to show percentages by department.
    
9. Number of Employees by Age Group
Displays the age distribution of employees.

        Visualization: Use a histogram with customizable age bins.
    
10. Job Satisfaction Ratings
Highlights employee satisfaction levels across different roles.

        Visualization: Use a heatmap to show satisfaction scores.
    
11. Education Field-wise Attrition
Analyzes attrition rates based on employees' education fields.

         Visualization: Horizontal bar chart for clear comparisons.
    
12. Attrition Rate by Gender and Age Group
Combines gender and age group to provide detailed attrition trends.
 
         Visualization: Use nested pie charts or bar charts.

## Technical Configuration:

1. Tools: Tableau Desktop, MS SQL Server, Microsoft PPT

2. Data Source: [Specify the source, e.g., Excel, SQL Database]

3. Key Metrics: Employee Count
   Attrition Rate
   Average Age
   Job Satisfaction Scores

4. Calculated Fields:
Active Employees = Total Employees - Attrition Count
Attrition Rate (%) = (Attrition Count / Total Employees) × 100

## Conclusion:

This dashboard offers a comprehensive view of HR metrics, enabling data-driven decisions to improve employee retention and satisfaction. Future improvements can include additional filters for more granular analysis and real-time data integration.

   
