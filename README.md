# HR-ATTRITION

## HR Attrition Analysis:Reducing Attrition Rate From 16% to 2%

## Introduction:
HR Attrition Analysis is a comprehensive examination of the factors influencing employee attrition within IBM, a global technology and consulting company. Attrition is the voluntary and involuntary departure of employees from an organization, which can have profound effects on the company’s performance, productivity, and overall workforce stability.

This analysis delves into the various aspects of HR attrition within IBM, aiming to provide valuable insights into the underlying causes, patterns, and trends associated with employee turnover. By examining factors such as job satisfaction, career development opportunities, work-life balance, compensation and benefits, and stock option opportunity, this analysis seeks to shed light on the reasons why employees choose to leave IBM and how the company can address these issues effectively.

The goal of the HR Attrition Analysis is to provide actionable insights that enable IBM’s human resources department and management to make informed decisions and implement effective retention strategies. By identifying the root causes of attrition and implementing targeted interventions, IBM can reduce turnover, enhance employee satisfaction, and cultivate a strong and resilient workforce capable of driving innovation and achieving organizational objectives.

## IMPLEMENTATION OUTLINE

## Analytics process:
The tool I will use for this case study is MS Excel 2021. [download](hppts//microsoft.com)
The data analytics process will follow the PMAVD (Prepare, Model, Analyze, Visualize and Dashboard) process.
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


## BELOW IS THE DATASET BEFORE CLEANING 

![ibm2](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/9b555638-0fea-42d0-99d0-941a3c78da2f)


![ibm3](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/ad49e9a2-6efa-4583-ad6a-f0821ed117ba)

![ibm4](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/9da42be0-8e66-4bfc-bd4f-e9eb05172e8f)
![ibm5](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/fa96e3f6-20b0-45b6-9962-5eb8e2e945a7)

## REMOVING COLUMNS THAT I DONT WANT TO USE FOR THE ANALYSIS

![ibm6](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/e7357ec3-f85a-4d07-b7e8-431625b20bf2)

## DATA TRANSFORMATION
Some columns “Education” contains numbers (1–5) only.I replaced the numbers with their true values. Then, change datatype to “Text” with the help of conditional column.

Created a conditional column and replace all numerical values with the appropriate  values.

## steps in creating conditional columns
Click on “Add Column”, Select “Conditional Column”, type in the new column name (Educational Level) and define the new values for the new columns.
I added some columns like performance status, education level etc with help of conditional column by Following the same steps i took to creating condition column for the “Educational Level” column and create for the columns listed above. 

![ibm7](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/f9232dca-8cb0-4602-b601-ff8d81e07b7b)


## Closing ans loading
AFTER THE WHOLE CLEANING PROCESS, I CLOSED AND LOAD THE DATA BACK TO EXCEL FOR ME TO CARRY OUT AN ANALYSIS KNOWN AS DATA MODELING WITH THE HELP OF A TOOL CALLED PIVOT TABLE


## DATA MODELING  AND ANALYSIS USING PIVOT TABLE
From the pivot table I generated all the necessary KPI like

## Total employee
## Active employee
## Inactive employee(ATTRITION)
## Retention rate etc.
## Also the reasons why employees leave the organization with the help of charts and graph where gotten from this pivot table analysis as shown below
![ibm11](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/477ba552-a210-4654-9d2b-a1d844bd1a70)
![ibm13](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/06649f59-900b-4b0d-b0e8-09ba8516082c)
![ibm10](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/252311ae-85fb-4bef-8a5a-8121555a126e)
![ibm12](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/4c331aea-3adf-48aa-a25f-22f8a9f1a1c2)

## VISUALS AND DASHBOARD INSIGHT
![HR NEW DASH](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/33647940-0ddd-4991-80bf-f226b51b12bc)
[view dashboard link](https://1drv.ms/x/c/0635e6a846394b35/EQnj7h0k0w5CjqmOQEq7XusBvNxWE4GTj9mBNL-WxMNZ_g?e=zXAg2E)

## REDUCING ATTRITION RATE  TO 2% AND INCREASING RETENTION RATE TO 98%
![ATTRITION REDUCED](https://github.com/asogwachinenye1/HR-ATTRITION/assets/161091047/fa90abde-644d-4d28-87f3-6970a67ca7a3)
By increasing employees salary and removing overtime will help to reduce attrition rate to 2%..Overtime can be replaced with shift work.
[link](https://1drv.ms/x/c/0635e6a846394b35/EQnj7h0k0w5CjqmOQEq7XusBvNxWE4GTj9mBNL-WxMNZ_g?e=GGqBJw)
## RECOMENDATIONS
## Comprehensive Exit Interviews:
Conduct thorough exit interviews with departing employees to understand the reasons behind their decision to leave. Use this information to identify patterns and areas for improvement within the organization.

## Employee Engagement Surveys: 
Regularly administer employee engagement surveys to assess job satisfaction, work-life balance, career development opportunities, and overall organizational culture. Use the feedback to implement targeted interventions to address areas of concern.

## Retention Programs:
Develop and implement retention programs tailored to address the specific needs of different demographic groups, job levels, and departments within the organization. These programs could include mentorship initiatives, career development pathways, and recognition programs.

## Flexible Work Arrangements: 
Offer flexible work arrangements such as remote work options, flexible scheduling, and compressed workweeks to accommodate employees' diverse needs and improve work-life balance.

## Training and Development: 
Invest in training and development programs to upskill employees and provide opportunities for career advancement. Providing clear pathways for growth within the organization can improve employee satisfaction and retention.

## Fair Compensation and Benefits: 
Ensure that compensation and benefits packages are competitive and equitable across the organization. Regularly review salary structures and adjust them to reflect market trends and employees' contributions.

## Leadership Development: 
Provide leadership development programs for managers and supervisors to enhance their skills in employee engagement, communication, and conflict resolution. Strong leadership can positively impact employee morale and retention.

## Workload Management:
Implement workload management strategies to prevent burnout and excessive stress among employees. This could include redistributing tasks, setting realistic goals and deadlines, and promoting a culture of work-life balance.

## Promote Inclusivity and Diversity: 
Foster an inclusive and diverse workplace culture where all employees feel valued, respected, and supported. Address unconscious bias and discrimination through training programs and policy initiatives.

## Regular Communication and Feedback: 
Maintain open channels of communication between employees and management. Encourage regular feedback sessions and address concerns and suggestions in a timely manner.

## Employee Wellness Programs:
Implement wellness programs that promote physical, mental, and emotional well-being. This could include access to counseling services, fitness programs, mindfulness workshops, and health screenings.

## Recognition and Rewards:
Recognize and reward employees for their contributions and achievements. This could be through formal recognition programs, bonuses, promotions, or other forms of appreciation.
