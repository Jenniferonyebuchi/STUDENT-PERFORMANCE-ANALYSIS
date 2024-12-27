# STUDENT-PERFORMANCE-ANALYSIS
![student performance analysis cover 1](https://github.com/user-attachments/assets/89b70e32-8219-4596-a884-f868dfdf975e)

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


### Analysis and Visualization:
---
The Dashboard comprises of these visuals:
#### Student Count by Gender:
![image](https://github.com/user-attachments/assets/281ef560-91e6-4597-8341-a41b8df9a9d3)
* Out of a total of 1000 students, 51.8% are females while 48.2% are males.
  
#### Student Count by Parental Level of Education:
![image](https://github.com/user-attachments/assets/7f1fecdd-eec3-4155-bea3-0378773c6bdd)
* The majority of the students, 226 in total, had parents with some college education, while 59 students had parents with master's degrees.
  
#### Student Count by Race/Ethnicity:
![image](https://github.com/user-attachments/assets/1c776d94-3a44-4f68-b2cb-a05aad9cc364)
* Group C had the most population of students corresponding to 319 students while Group A had the least student population corresponding to 89.

#### Student Count by Parental Level of Education and Race/Ethnicity:
![image](https://github.com/user-attachments/assets/b1c0fee7-14d4-44d0-bd9f-26de0e612c61)
* Group C had the highest number of parents with associate degrees, high school, some college, and bachelor's degrees. Group D had the highest number of parents with some high school and master’s degrees, while Group A had the lowest population of parents across all levels of education.

#### Student Count by Lunch type:
64.5% of the students opted for standard lunch while 35.5 of them chose the free/reduced lunch option.

#### Student Count by Test preparation course:
Only 22.7% of the students completed the test preparation course while 41.8% didn’t.

The students' average math, reading and writing scores were 66.09%, 69.17% and 68.05% respectively. However, when compared across genders, Males perform better in math with an average of 68.73 while females excel in reading and writing with: 72.6 and 72.47 averages respectively. 

