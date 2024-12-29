# STUDENT-PERFORMANCE-ANALYSIS
![student performance analysis cover 1](https://github.com/Jenniferonyebuchi/STUDENT-PERFORMANCE-ANALYSIS/blob/main/student%20performance%20analysis%20cover%201.JPG)

### Introduction
---
This report provides an in-depth analysis of student performance, including demographic insights, academic trends, and high-performance patterns. The dataset comprises columns such as gender, parental education level, race/ethnicity, test preparation course, and scores in mathematics, reading, and writing.
The visualizations are created using Power BI, and this document outlines the key findings and potential use cases.

### Skills demonstrated for the project:
***
* Data Cleaning,
* Data Visualization,
* Quick Measure,
* Filters, Tooltips,
* Critical Thinking,
* Problem Solving.

### Problem Statement 
---
1.	Analyze student demographics to understand trends.
2.	Evaluate academic performance by gender, parental education, test preparation course and ethnicity.
3.	Identify high-performing students.
4.	Explore the impact of test preparation, parental education, etc  on scores.

### Data Source:
I obtained the data from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

### Data Columns
---
1.	Gender: Gender of the students.
2.	Race/Ethnicity: Ethnic group of the students.
3.	Parental Level of Education: Highest educational attainment of parents.
4.	Lunch: The lunch type the student was subscribed to
5.	Test Preparation Course: Whether a student completed a test preparation course.
6.	Math Score: Student's score in mathematics.
7.	Reading Score: Student's score in reading.
8.	Writing Score: Student's score in writing.

### Data Transformation
***
The dataset had no unique identifier, hence I had to create two new measures to show the student count and high performers.

Student Count

![image](https://github.com/user-attachments/assets/c8f3dd4d-ec36-4644-892e-1cf0b47b88bf)

High Performers

![image](https://github.com/user-attachments/assets/d85a6a7d-d49e-494b-b267-772bf3a13733)


### ANALYSIS AND VISUALIZATION
---
To ensure clarity, the Dashboard has four pages of visuals:

* Student Count Analysis- This page provides insights into the total number of students, including their distribution based on gender, demographics, and other relevant categories.

* Average Scores Analysis - This page highlights the trends in average scores across subjects, parental level of education, etc, offering a comprehensive view of overall academic performance.

* High-Performance Analysis - This page focuses on top-performing students, identifying patterns, factors contributing to their success, and how they compare to overall student performance.
  
* Impact Tree- This page shows the impact of Gender, Test preparation course, Race/Ethnicity, and Parental Level of Education on Students Performance

###Student Count Analysis
---
#### Student Count by Gender
![image](https://github.com/user-attachments/assets/281ef560-91e6-4597-8341-a41b8df9a9d3)
* Of 1000 students, 51.8% are females while 48.2% are males.
  
#### Student Count by Parental Level of Education
![image](https://github.com/user-attachments/assets/7f1fecdd-eec3-4155-bea3-0378773c6bdd)
* The majority of the students, 226 in total, had parents with some college education, while 59 students had parents with master's degrees.
  
#### Student Count by Race/Ethnicity
![image](https://github.com/user-attachments/assets/1c776d94-3a44-4f68-b2cb-a05aad9cc364)
* Group C had the most population of students corresponding to 319 students while Group A had the least student population corresponding to 89.

#### Student Count by Parental Level of Education and Race/Ethnicity
![image](https://github.com/user-attachments/assets/b1c0fee7-14d4-44d0-bd9f-26de0e612c61)
* Group C had the highest number of parents with associate degrees, high school, some college, and bachelor's degrees.
* Group D had the highest number of parents with some high school and master’s degrees, while Group A had the lowest population of parents across all levels of education.

#### Student Count by Lunch type

* 64.5% of the students opted for standard lunch while 35.5% chose the free/reduced lunch option.
#### Student Count by Test Preparation Course

* Only 35.8% of the students completed the test preparation course while 64.2% didn’t.

#### Average Scores Analysis
---
#### Subject Averages

* The students' average math, reading and writing scores were 66.09%, 69.17% and 68.05% respectively. 

#### Average scores by Gender

* When the average scores were compared across genders; Males performed better in math with an average of 68.73 while females excelled in reading and writing with: 72.6 and 72.47 averages respectively.

#### Average scores by Race/Ethnicity

* When the averages were compared across race/ethnicity; Groups A, B and C performed below average while Groups D and E performed above average.
* Group E had the highest averages (73.82, 73.03, 71.41 respectively) while Group A had the lowest averages corresponding to 61.63, 64.67, 62.67.

#### Average scores by Parental Level of Education

* Parental level of education significantly impacted the students' average performance.
* Students whose parents had high school or some high school scored below average whereas, those  whose parents attained some college education, a bachelor's degree, a master's degree, or an associate degree performed above average.
* The highest average scores were achieved by students whose parents held master's degrees, while the lowest averages were observed among students whose parents had high school education.

#### Average scores by Test Preparation Course

* Students who completed the test preparation course performed above average while those who didn't performed below average.

#### High-Performance Analysis
 ---
#### High Performers by Student Count
 
* Only 2.25% of the student population achieved an average score above 90 across the three subjects, qualifying them as high performers.

#### High Performers by Gender

* Females outperformed their male counterparts, accounting for 73.91% of the high performers, while males comprised 26.09%.
  
#### High Performers by  Race/Ethnicity
* Group E had the highest number of high performers, while Groups A and B had the lowest.
  
#### Impact of Parental Level of Education on Student Performance

* Out of the 23 high performers, 9 were students whose parents held bachelor's degrees, while none of the high performers came from students whose parents had a high school education.

#### Impact of Test Preparation Course on Student Performance
* 60.87% of the high performers completed the test preparation Course while 39.13% didn't.

#### Impact of  Race/Ethnicity and Parental Level of Education on Student Performance
The possibility of students from Group E who completed the test preparation course and whose parents had bachelor's degrees finishing as high performers is very high compared to any other category of students.

#### Impact Tree
Female students who completed the Test Preparation Course from Group E whose parents had a bachelor's degree education had higher chances of becoming high performers than any other category of students.

### Conclusions and Recommendations
---
* Students who opted for standard lunch made up a significant majority (64.5%), potentially indicating a socioeconomic divide that could influence performance.
Support should be provided for such students with Lower Socioeconomic Backgrounds.

* Students' performance correlates strongly with parental education level. There is a need to implement targeted academic support and mentorship programs for students whose parents have lower education levels or who opt for free/reduced lunch.
Expand Test Preparation Courses

* Increase participation in the test preparation course by offering incentives and accessibility to students from underperforming groups, such as Groups A and B.
Focus on Gender-Specific Interventions

* Provide tailored resources to bridge the gender gap in math for female students and reading/writing for male students, ensuring balanced academic growth. There's need to leverage Parental Involvement

* Engage parents through workshops to raise awareness of how their educational background influences their children's performance and encourage their active involvement in academic support.
Target Underperforming Groups

* Address disparities in performance across racial/ethnic groups by providing culturally tailored learning programs and resources to support students from Groups A, B, and C.

* There's a need to study the strategies and environments contributing to Group E's success and replicate them across other groups to boost overall performance.
Comprehensive Student Support

* Develop a holistic student support framework that considers gender, parental education, socioeconomic background, and race/ethnicity to ensure equitable opportunities for all students.
