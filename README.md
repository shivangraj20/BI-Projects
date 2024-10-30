
 # HR Analytics Dashboard: Understanding Employee Attrition

## Overview
This Power BI dashboard provides insights into employee attrition by analyzing key factors such as age, years at the company, job role, education, salary, department, and more. The goal is to help the company understand the reasons behind employee turnover and take data-driven actions to improve retention rates.

### Dashboard Link : https://app.powerbi.com/groups/me/reports/be778904-e179-4319-942a-089584ff3a44/f2ad0d28e038a95c577d?experience=power-bi


## Problem Statement
Employee attrition is a major concern for companies. Understanding the key reasons why employees leave the company helps identify areas that need attention and improvement, thereby enabling strategic initiatives to improve employee satisfaction and retention.

## Dataset
- **Source**: https://docs.google.com/spreadsheets/d/1I-8IccMYTbkNiLH24ACwLQ3kUQ3djY6R7mRwbk57BWs/edit?gid=2050143334#gid=2050143334
- **Contents**: The dataset includes employee demographic information, job roles, salary details, education levels, tenure, and ratings of various work aspects.

## Features
This dashboard includes the following key features:
- Interactive charts and slicers to filter data based on age, job role, department, and other key factors.
- Key metrics such as overall attrition rate, tenure analysis, and satisfaction levels.
- Detailed visuals that highlight correlations between attrition and demographics.

## Visualizations
1. **Attrition Rate by Department**: A bar chart showing which departments have the highest attrition rates.
2. **Correlation Heatmap**: A heatmap representing the relationship between factors like age, job satisfaction, compensation, and attrition.
3. **Attrition by Age and Gender**: A stacked bar chart to show age groups and gender-wise attrition trends.
4. **Satisfaction Ratings Analysis**: Visual representation of ratings on key factors like work-life balance, career growth, and manager relationships.
5. **attrition rate by salary.
6. **attrition rate by years at company
7. **attrition rate  by job role. 

## Getting Started
Follow these instructions to view and interact with the dashboard:

### Prerequisites
- **Power BI Desktop**: You can download it from [here](https://powerbi.microsoft.com/desktop/).
- Any additional tools required.

### Installation & Setup
1. Clone this repository using the command below:
   ```bash
   git clone https://github.com/shivangraj20/BI-project.git



### Steps followed 

- step1 - Data Loading and Inspection

Load the dataset into Power BI Desktop. The dataset includes information about employee demographics, job roles, education, salary, and tenure.
Open the Power Query Editor to perform an initial inspection of the dataset’s column quality, column distribution, and column profile.
Set column profiling to use the entire dataset to ensure an accurate representation of the data quality.
- step2 -Data Cleaning and Preparation

Identify columns with missing or erroneous values and address them. For instance, if some columns such as "Job Satisfaction" or "Last Performance Rating" contain null values, those records were excluded from calculations where those values are relevant.
Create new calculated columns to derive additional information such as:
Age Groups: Categorize employees into age groups like “20-30,” “30-40,” etc.
Tenure Categories: Classify employees based on their years at the company (e.g., “Less than 1 year,” “1-3 years,” “3-5 years,” and “5+ years”).

- step3 - Identifying Key Factors for Attrition
The primary factors considered in this analysis include:

Age Factor: Employee age groups and how they relate to attrition rates.
Years at Company: Analyzing whether tenure length correlates with higher turnover.
Job Role: Determine if certain roles are more susceptible to turnover.
Education Level: Understanding how education impacts employee retention.
Salary and Compensation: Assessing whether salary levels influence the likelihood of attrition.
Department: Identifying departments with higher attrition rates.

- step4 - Building Visualizations

Create key visualizations to present insights:

Attrition Rate Cards
Create metric cards to show overall attrition rates and the average tenure of employees leaving the organization.

Department-wise Attrition Analysis
Add a clustered bar chart to display attrition rates segmented by department. This helps identify departments where turnover is particularly high.

Age Group and Gender Analysis
Use a stacked bar chart to show attrition segmented by age group and gender, identifying if younger employees or a specific gender are leaving more frequently.

Salary and Job Role Analysis
Implement a scatter plot to depict the relationship between job roles and salary levels, indicating which roles face higher attrition due to salary concerns.

Heatmap to Show Correlation
Include a heatmap to show the correlation between factors such as salary, job satisfaction, and employee attrition. This helps visualize which factors have the strongest relationships with turnover.

Satisfaction Ratings Visuals
Add a ratings visual to display employee feedback on different aspects like:

Job Satisfaction
Work-Life Balance
Manager-Employee Relationship
Career Growth Opportunities
Recognition and Reward
Ratings data with values of zero (indicating "Not Applicable") are excluded from calculations to ensure accurate representation.

- step5 - Filter Setup for Enhanced Interactivity
Add slicers to enable users to filter data based on key demographic factors such as “Department,” “Job Role,” “Education Level,” and “Age Group.” This provides flexibility in exploring how different factors contribute to attrition.

- step6 - Deriving Insights
Analyze the visualizations and key metrics to derive actionable insights:

Identify High Attrition Roles and Departments: Determine the job roles and departments with the highest attrition rates and explore potential reasons like lack of growth opportunities or insufficient salary levels.
Correlation Between Age and Attrition: Assess if younger or more experienced employees are leaving more often and whether this correlates with job satisfaction or compensation issues.
Impact of Salary on Turnover: Examine whether employees with lower salary ranges show higher turnover, indicating potential pay dissatisfaction.
Job Satisfaction and Manager Relationship: Evaluate if low job satisfaction or strained manager relationships are primary drivers of turnover.

-step7 - Recommendations for Retention
Based on the findings:

Suggest improvements in departments or roles with high attrition, such as increasing salaries, offering more career development opportunities, or improving work-life balance policies.
Propose targeted employee engagement strategies for specific age groups or demographics that show higher turnover.
Highlight the importance of fostering better manager-employee relationships and recognition systems to improve job satisfaction.


- step8 -Final Touches on the Dashboard

Add a company logo, key titles, and a professional theme to maintain consistency and branding.
Insert explanatory text boxes to describe each visual briefly, ensuring users understand the story each chart or metric tells.
Create a summary section in the dashboard that highlights the top findings and recommendations based on the analysis
