# HR-ATTRITION

## HR Attrition Analysis: Unraveling Employee Turnover Patterns

## Introduction:
HR Attrition Analysis is a comprehensive examination of the factors influencing employee attrition within IBM, a global technology and consulting company. Attrition is the voluntary and involuntary departure of employees from an organization, which can have profound effects on the company’s performance, productivity, and overall workforce stability.

This analysis delves into the various aspects of HR attrition within IBM, aiming to provide valuable insights into the underlying causes, patterns, and trends associated with employee turnover. By examining factors such as job satisfaction, career development opportunities, work-life balance, compensation and benefits, and stock option opportunity, this analysis seeks to shed light on the reasons why employees choose to leave IBM and how the company can address these issues effectively.

The goal of the HR Attrition Analysis is to provide actionable insights that enable IBM’s human resources department and management to make informed decisions and implement effective retention strategies. By identifying the root causes of attrition and implementing targeted interventions, IBM can reduce turnover, enhance employee satisfaction, and cultivate a strong and resilient workforce capable of driving innovation and achieving organizational objectives.

## IMPLEMENTATION OUTLINE

## Analytics process:
The tool I will use for this case study is MS Excel 2021. The data analytics process will follow the PMAVD (Prepare, Model, Analyze, Visualize and Dashboard) process.
## Data Source: 
# Kaggle 
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

PS: This is a fictional dataset created by IBM data scientists

### DATA CLEANING
# a. Preparation: I deployed the OMG-C method in the data preparation step. Objectives, Measures, Get and Clean the data.

# Objective:
Calculate the necessary KPI
Using an interactive visual, explore the top five reasons why employees leave the organization

# b. Measures:
The dataset for this task has thirty-six columns which contains Age,Attrition,BusinessTraveL,DailyRate,Department,DistanceFromHome,Education,EducationField,EmployeeCount,EmployeeNumber,EnvironmentSatisfaction,Gender,HourlyRate,JobInvolvement,JobLevel,JobRole,JobSatisfaction,MaritalStatus,MonthlyIncome,MonthlyRate,NumCompaniesWorkedOver18OverTime,PercentSalaryHike,PerformanceRating,RelationshipSatisfaction,StandardHours,StockOptionLevel,TotalWorkingYears,TrainingTimesLastYear,WorkLifeBalance,YearsAtCompany,YearsInCurrentRole,YearsSinceLastPromotion,YearsWithCurrManager. Total of 1,470 rows

## 2. Exploratory Data Analysis (EDA)
EDA are a set of steps used to explore and understand the data better before cleaning and transformation.

a. Cleaning and Transformation

- Convert dataset into table: Ctrl A, Ctrl T, “OK”

- Export to power query: Go to “Data”, Select “From table”.

- Check for number of rows: Go to “Transform”, Select “Count Rows”

Columns: 36 Rows: 1470


## BELOW IS THE DATASET BEFORE CLEANING 1





## REMOVING COLUMNS THAT I DONT WANT TO USE FOR THE ANALYSIS


## DATA TRANSFORMATION
Some columns “Education” contains numbers (1–5) only.I replaced the numbers with their true values. Then, change datatype to “Text” with the help of conditional column.

Created a conditional column and replace all numerical values with the appropriate  values.

## steps in creating conditional columns
Click on “Add Column”, Select “Conditional Column”, type in the new column name (Educational Level) and define the new values for the new columns.
I added some columns like performance status, education level etc with help of conditional column by Following the same steps i took to creating condition column for the “Educational Level” column and create for the columns listed above. 



## Closing ans loading
AFTER THE WHOLE CLEANING PROCESS, I CLOSED AND LOAD THE DATA BACK TO EXCEL FOR ME TO CARRY OUT AN ANALYSIS KNOWN AS DATA MODELING WITH THE HELP OF A TOOL CALLED PIVOT TABLE


## DATA MODELING  AND ANALYSIS USING PIVOT TABLE
From the pivot table I generated all the necessary KPI like

# Total employee
# Active employee
# Inactive employee(ATTRITION)
# Attrition rate
# Retention rate etc.
# Also the reasons why employees leave the organization with the help of charts and graph where gotten from this pivot table analysis as shown below

### VISUALS AND DASHBOARD


DASHBOARD VISUALIZATION
### INSIGHTS:
After the whole analysis, visualization creation ,and reports to track the attrition key performance indicator :
Employee count =1470
Attrition count=234
Attrition rate=16.12%
Retention rate=84%



RECOMMENDATION

Attrition Analysis:

Identify reasons for the high attrition rate among inactive employees. Conduct exit interviews or surveys to understand their dissatisfaction and address any underlying issues.
Monitor attrition trends by gender, education level, job role, and environmental satisfaction to pinpoint areas for improvement and implement targeted retention strategies.

Employee Engagement:

Focus on improving job satisfaction and environmental satisfaction for better employee retention.
Provide opportunities for career development and growth to increase employee engagement and loyalty.

Work-Life Balance:

Assess the impact of business travel on attrition rates. Consider implementing flexible work arrangements or travel policies to support employees’ work-life balance.

Performance Management:

Review performance status across departments to identify any correlation with attrition rates. Offer additional support or training to underperforming employees to improve job satisfaction and retention.

Diversity and Inclusion:

Ensure equal opportunities and a supportive work environment for employees of all genders, marital statuses, and age groups to foster inclusivity and reduce attrition.

Departmental Analysis:

Analyze attrition rates by department and address any disparities or challenges specific to each department to improve overall retention.

Age Group Analysis:

Consider tailoring retention strategies based on different age groups’ needs and preferences to effectively retain talent across all demographics.

Continuous Monitoring:

Regularly review and update the attrition dashboard to track progress and adjust strategies as needed to maintain a healthy retention rate.
By implementing these recommendations, you can effectively address attrition issues and improve employee retention within the organization.
