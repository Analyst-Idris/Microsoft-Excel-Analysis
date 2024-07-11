# Employee Attrition Analysis

![Home Page](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/db05aa51-1c10-4e33-85de-27def8660971)
---

## Introduction
---
This is a Microsoft Excel project on employee attrition analysis within an imaginary organization called **X and Y Global Company**.
This project aims to analyze employee attrition within **X and Y Global Company** by exploring various factors such as education field, business travel frequency, job satisfaction, and more. The goal is to identify key insights that can help improve employee retention and job satisfaction.
**_Disclaimer_** : _All dataset and reports do not represent any company, institution of any state or country, but just a dataset to demonstrate the capabilities of Microsoft Excel._

## Problem Statement

The **X and Y Global Company** is experiencing a high rate of employee attrition, negatively impacting overall productivity, morale, and increasing recruitment and training costs. The primary objective of this analysis is to identify key factors contributing to employee attrition and provide actionable insights to develop effective retention strategies. By understanding the underlying causes of attrition, the company can address specific issues and create a more supportive and engaging work environment that encourages employee retention and satisfaction.

## Dataset:
The dataset includes various employee attributes such as age, gender, job role, distance from home, education field, marital status, job satisfaction, as well as the annual salary across the various job roles.

## Data Exploration
**Age Group** : The age range of the employee, categorized into predefined intervals.

**Attrition**	: Indicates whether the employee has left the company (Yes) or is still employed (No).

**BusinessTravel** : The frequency with which the employee travels for business purposes.

**Department** : The department where the employee is currently working.

**Distance From Home** : The distance between the employee's home and the workplace, measured in miles or kilometers.

**Distance** :  Distance represented by numerical codes.

**Education** :	The highest educational level attained by the employee, represented by numerical codes.

**Education Field** : The field of study in which the highest level of education was completed.

**EmployeeCount** :	A constant value representing the count of individual employee entries (always 1 for individual records).

**EmployeeID** : A unique identifier assigned to each employee in the dataset.

**Gender** : The gender of the employee.

**JobLevel** : The hierarchical level of the employee within the organization, represented by numerical codes.

**JobRole** :	The specific job title or role of the employee within the company.

**MaritalStatus** :	The marital status of the employee (Single, Married).

**MonthlyIncome** :	The monthly salary of the employee, expressed in currency units.

**Job satisfaction** : The level of job satisfaction represented by numerical codes.

## **Methodology**
---
## Data Preparation and Visualization 

The dataset underwent a thorough cleaning process to ensure its accuracy, consistency, and usability for analysis. Here are the key steps taken during the data cleaning process:

# **1.	Handling Missing Values**:

•	Missing values were identified and handled to ensure data completeness. Appropriate techniques like imputation or removal of records with missing values were applied depending on the extent and importance of the missing data.

# **2.	Categorizing Variables**:

•	To enhance analysis, variables were categorized into meaningful groups. This transformation was applied to several columns:

# **Job Satisfaction**:

•	Initially recorded as numerical values (1, 2, 3, 4), job satisfaction was transformed into descriptive categories for better understanding:

	1: Dissatisfied, 
	2: Satisfied,
	3: Very dissatisfied,
  4: Very satisfied.
  This transformation helped gain deeper insights into employees' satisfaction levels.
  
# **Distance from Home**: 

•	Distance from home was initially recorded as numerical values. For better understanding, these values were categorized into four groups:

Far,
Moderate,
Near,
Very Far.

•	This categorization helped analyze how distance from home affects employees' interest in their current job.

# **Age Group**:

•	Various ages were grouped into brackets to facilitate better understanding and analysis of age-related trends.

# **Department**:

•	Department names were abbreviated for readability and ease of analysis:

*Human Resources (HR)*
*Research and Development (R&D)*

# **3.	Data Transformation and Pivot Table Creation**:

•	After categorizing the variables, the dataset was transformed into pivot tables. This segmentation and summarization of data enabled effective data-driven decision-making

## **•	Preview of data before cleaning**

![preview of dataset before cleaning](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/9245685d-630a-4730-91ee-a2b24539d0e9)

## **•	Preview of data after cleaning in table form** 


![preview of dataset after cleaning](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/dbd03937-1b24-4bb7-8285-0948d2fa4817)


## **•	Key Performance Indicators (KPIs)**

![KPIs](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/951f80aa-422d-4ea1-a7f2-cad8d8258e3e)

## **•	Tivot table**  

![pivottable](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/75026fca-cdc3-4197-88a1-913722024e35)


## **•	Slicers**



![Slicer](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/74c1f2e4-66d6-4845-86cb-6503ff767f9f)



•	For visualization, various charts, including bar charts, column charts, and donut charts, were utilized. These visualizations were compiled into an interactive dashboard alongside the summarized tables to facilitate improved data-driven decisions. 


![Employee Dashboard 1](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/e332a236-1836-4812-b4e4-4d704d5d9074)


## **SUMMARY OF THE KEY INSIGHTS**

# *Employee attrition is a critical issue that organizations strive to manage effectively. The above dashboard offers a detailed overview of various factors influencing attrition numbers, spanning across education fields, business travel, job satisfaction, distance from the workplace, gender, marital status, age groups, job roles, and departments. Analyzing these factors can provide invaluable insights into where organizations might focus their retention efforts.*


Attrition number vary significantly across different education fields. Employees with a background in Life Sciences exhibit the highest attrition rate at 303, followed closely by those in the *Medical field* with (225). Conversely, those in Marketing (75), *Technical Degrees* (45), *Human Resources* (33), and *Other fields* (30) show relatively lower attrition rates. This trend may suggest that employees with specialized education in Life Sciences and Medical fields might be more prone to seeking opportunities elsewhere, possibly due to higher demand for their skills or better prospects in other organizations.
The frequency of business travel also appears to have a significant impact on attrition level. Employees who travel rarely have the highest attrition rate of 468, indicating that infrequent travel might be linked to dissatisfaction or a lack of engagement with their roles. Those who travel frequently show a substantial attrition rate of 207, while non-traveling employees have the lowest attrition rate of 36. This data suggests that a balance in travel requirements might be key to retaining employees, as too much or too little travel can contribute to turnover.
Job satisfaction is a crucial determinant of employee retention. Unsurprisingly, dissatisfied employees have the highest attrition rate of 219, followed by very dissatisfied employees at 157. In contrast, employees who are very satisfied (197) and satisfied (138) with their jobs exhibit lower attrition’s   number. These figures underscore the importance of fostering a positive work environment and addressing factors that contribute to employee dissatisfaction to reduce turnover.
The proximity of employees' residences to the workplace also plays a significant role in attrition. Employees living near the workplace have the highest attrition rate at (372), which might indicate that proximity alone does not guarantee job satisfaction. Those living at a moderate distance have an attrition number of (159), while employees living far (108) and very far (72) have lower attrition rates. This pattern suggests that factors other than mere distance, such as work-life balance and job satisfaction, are more influential in driving employee retention.
Certain job roles have higher attrition than others. Sales Executives (165), *Research Scientists* (159), and *Laboratory Technicians* (126) have the highest attrition rates. Other roles, including *Research Director*, *Healthcare Representative*, *Manufacturing Director*, *Manager*, *Sales Representative*, and *Human Resource*s, show lower attrition rates. These trends could reflect varying levels of job satisfaction, career advancement opportunities, and work-life balance across different roles.
Number of attritions also differ significantly across departments. The *R&D* department has the highest attrition rate at (453), followed by the *Sales department* at (201). The *HR* department has the lowest attrition rate at (57). These figures highlight the need for targeted retention strategies tailored to the specific challenges and dynamics of each department.



![Employee Dashboard 2](https://github.com/Classicidris/Microsoft-Excel-Analysis/assets/141183966/499c4659-8180-4cf8-b310-9b5d8aff5564)


## **SUMMARY OF THE ABOVE TABLE**

# *Employee attrition is a critical issue for organizations, impacting both productivity and financial performance. The provided table offers a detailed overview of employee attrition rates across various job roles, the count of employees in each role, and their total monthly income. By analyzing these factors, I helped organization gain valuable insights into where such organizations should focus their retention efforts.*



Among the job roles, **Sales Executives** stand out with the highest number of employees and attritions. With 978 employees and 165 attritions, this role also boasts the highest total monthly income of $63,752,580. The high attrition rate suggests that despite the lucrative income, employees in this role might be experiencing significant job-related challenges or finding better opportunities elsewhere.


**Research Scientists** also exhibit a high attrition rate, with 159 out of 876 employees leaving their positions. This role accounts for a total monthly income of $56,918,700, the second-highest among the listed roles. The considerable attrition rate in this high-income bracket indicates a potential misalignment between job expectations and actual job experiences.


**Laboratory Technicians**, with 777 employees and 126 attritions, have the third-highest total monthly income at $51,526,020. This role’s high attrition rate suggests that even with a substantial workforce, the organization may need to address underlying issues affecting employee satisfaction and retention.


**Manufacturing Directors**, though fewer in number with 435 employees, experience a moderate attrition rate of 48. Their total monthly income stands at $30,094,920. The lower attrition rate compared to the previously mentioned roles may indicate better job satisfaction or less competitive external opportunities for employees in this position.


**Healthcare Representatives** have a moderate attrition rate of 57 out of 393 employees, with a total monthly income of $23,966,610. This suggests that while this role is moderately stable, there may still be areas needing improvement to further reduce attrition.


**Managers**, with 306 employees and 42 attritions, and a total monthly income of $19,399,140, exhibit relatively low attrition. This indicates a potentially higher job satisfaction level or better alignment with employee expectations, contributing to a more stable workforce.


**Sales Representatives**, having 249 employees and 36 attritions, generate a total monthly income of $16,277,370. The low attrition rate in this role suggests that employees may find their job roles and compensation packages satisfactory, leading to better retention.


**Research Directors**, with 240 employees and 57 attritions, earn a total monthly income of $15,713,550. Despite the lower number of employees, the moderate attrition rate indicates potential areas for improvement in job satisfaction or working conditions for these employees


Finally, the **Human Resources role**, with the fewest employees at 156 and the lowest attrition rate of 21, has a total monthly income of $9,130,380. This role’s low attrition rate and total income suggest a relatively stable and satisfied workforce, possibly due to effective HR policies and practices.

## **RECOMMENDATIONS FOR REDUCING EMPLOYEE ATTRITION**

*Employee attrition presents a significant challenge for organizations, as high turnover rates can negatively impact productivity and financial performance. Based on the analysis of the provided data on various factors influencing attrition rates, including job roles, education fields, business travel, job satisfaction, and distance from the workplace, the following recommendations are proposed to address and reduce employee attrition effectively*:

**Enhance Employee Engagement and Satisfaction** : Job satisfaction is a crucial determinant of employee retention, as evident from the high attrition rates among dissatisfied and very dissatisfied employees. Organizations should prioritize fostering a positive work environment by implementing regular employee feedback mechanisms, recognizing and rewarding employee contributions, and promoting a culture of open communication. Providing opportunities for career growth and professional development can also boost job satisfaction. Tailored programs that address specific job-related challenges and improve overall work-life balance will contribute significantly to reducing attrition.

**Develop Targeted Retention Strategies for High Attrition Roles** : Certain job roles, such as Sales Executives, Research Scientists, and Laboratory Technicians, exhibit higher attrition rates despite substantial monthly incomes. To address this, organizations should conduct thorough exit interviews to understand the specific reasons behind employee departures in these roles. Based on these insights, targeted retention strategies can be developed, such as offering competitive compensation packages, providing clear career advancement pathways, and enhancing job role clarity. Additionally, mentoring and support programs can help employees navigate job-related challenges effectively.

**Balance Business Travel Requirements** : The frequency of business travel has a significant impact on attrition rates, with employees who travel rarely exhibiting the highest attrition. To mitigate this, organizations should strive to balance travel requirements. Ensuring that employees have a say in their travel schedules and providing adequate support for those who travel frequently can improve job satisfaction. Leveraging technology for virtual meetings and reducing non-essential travel can also help maintain a healthy balance, ultimately reducing attrition linked to business travel.

**Improve Work-Life Balance and Flexible Work Arrangements** : Proximity to the workplace and the ability to manage work-life balance are critical factors influencing employee retention. Employees living near the workplace still exhibit high attrition, indicating that proximity alone does not ensure job satisfaction. Organizations should consider offering flexible work arrangements, such as remote work options, flexible working hours, and compressed workweeks. By providing employees with greater control over their work schedules, organizations can improve work-life balance, reduce burnout, and enhance overall job satisfaction, leading to lower attrition rates.

**Implement Department-Specific Retention Programs** : Attrition rates vary significantly across departments, with the R&D department experiencing the highest attrition. Organizations should develop department-specific retention programs tailored to the unique challenges and dynamics of each department. For instance, in departments with high attrition rates, efforts should focus on improving job satisfaction, providing clear career development opportunities, and addressing any specific concerns raised by employees. Regularly monitoring and analyzing attrition data by department can help identify trends and implement proactive measures to retain top talent.
























  

  














