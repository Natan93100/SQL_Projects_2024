# Nathan Ben David - Data Analyst Portfolio
## About

Hi! I'm Nathan, a young motivated Data Analyst looking for his next endeavor.<br>A lil about me before we jump to qualifications and so;
I like Data, Seriously, i Do!<br>
I Enjoy going on to [Kaggle](https://www.kaggle.com/learn) every now and then, exploring a random data set,
analysing it, and come up with my own conclusions regarding it; Sometimes i'll even have business ideas based solely on the SQL analysis of the database.<br>
Besides that weird hobby of mine (right?!), I enjoy statsitics (especially weird correlations like in here : [tylervigen.com](https://www.tylervigen.com/spurious-correlations))
and the Brain Science Field (if you do also, I HIGHLY encourage you to give 'The Brain That Changes Itself a read) as well as modelling data regarding that field using TensorFlow and Scikit-learn Libraries in Python.<br>
professionaly speaking, I hold a B.sc of Economics with a minor in Data-Science; During my studies, I gained the ability to work with complex data and developed an eye for identifying patterns and trends.<br> I also gained experience in laboratory techniques, data management, and statistical analysis, which I believe will be valuable assets in my role as a data analyst.<br>
Besides my acadmic knowledge and tools, I also have a proffesional background in working as a data analyst where I gained most of my knowledge, skills and tools.
## Skills
- **Advanced SQL**: Data manipulation, complex joins, and query optimization
- **Python Modeling**: Machine learning, data preprocessing, and automation
- **Statistics**: Hypothesis testing, regression analysis, and probability
- **Tableau**: Data visualization, interactive dashboards, and storytelling
- **Excel & VBA**: Data analysis, automation, and dynamic reporting
## Table of Contents
[About](#about)

[Portfolio Projects](#Portfolio-Projects)
- SQL
  - [Job Market Insights and Skills Gap Analysis](#Job-Market-Insights-and-Skills-Gap-Analysis)
  - [Crime Raw Data Analysis USA 2020-2024](#Crime-Data-Project)

- Python
  - [Linear Regression Predictive Model](Linear-Regression-Predictive-Model)
- C
  - [Longest Continuous Sequence In Array](Longest-Continuous-Sequence-In-Array)  

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.
### SQL
### Job Market Insights and Skills Gap Analysis<br>
  **For the DataSet** [Click Here](https://drive.google.com/drive/folders/1moeWYoUtUklJO6NJdWo9OV8zWjRn0rjN)
 <br>
**Load Files:** [Link](https://github.com/Natan93100/SQL_Project_2024/tree/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/load)<br>

**Goal:**<br>
      The goal of this project is to analyze job postings and company data<br> to gain insights into job market trends, salary distributions,          and skill demands.<br>

**Description:**<br> 
This project explores job postings across various industries to uncover key trends in the job market.<br> The analysis focuses on salary trends, the relationship between job roles and skills, and the demand for specific technical competencies.<br> By leveraging a comprehensive database of companies, job postings, and skill requirements, the project offers valuable insights into which skills are highly sought after, potential salary expectations, and how these factors vary across different companies.<br>

**Data Enrichment and Normalization**<br>
**[Company Insights Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Data%20Enrichment%20and%20Normalization/Company%20Insights.sql)**<br>
**[Normalize Skill Data Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Data%20Enrichment%20and%20Normalization/Normalize%20Skill%20Data.sql)**<br>

**Trend Analysis**<br>
**[Job Posting Trends Over Time Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Trend%20Analysis/Job%20Posting%20Trends%20Over%20Time.sql)**<br>
**[Salary Analysis Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Trend%20Analysis/Salary%20Analysis.sql)**<br>


**Skills Demand Analysis**<br>
**[Most In-Demand Skills by Industry Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Skills%20Demand%20Analysis/Query%20for%20Most%20In-Demand%20Skills%20by%20Industry.sql)**<br>
**[Skills Correlation Query](https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Skills%20Demand%20Analysis/Skills%20Correlation.sql)**<br>

<img src="https://github.com/Natan93100/SQL_Project_2024/blob/main/Job%20Market%20Insights%20and%20Skills%20Gap%20Analysis/sql_Project_Business_2024/Skills%20Demand%20Analysis/5628d74f-ca14-41a3-8af3-f5a6a9e0ad5c.png" alt="Alt text" width="350" height="250"><br>

### PYTHON
### [Linear Regression Predictive Model<br>](https://github.com/Natan93100/SQL_Project_2024/blob/main/Python/Linear%20Regression%20Model.py)

**Goal:**<br>
The goal of this project is to predict the dependent variable based on changes in the independent variable by fitting
a straight line to the data that minimizes the difference between actual and predicted values.

**Description:**<br>
The linear regression model was implemented from scratch in Python using the core mathematical principles of Ordinary Least Squares (OLS).
By calculating the slope and intercept, the model captures the linear relationship between temperature and ice cream sales.
This custom implementation demonstrates fundamental machine learning skills, including data handling with NumPy,
deriving key model parameters (slope and intercept), and applying the model for prediction.

If you are not familiar with linear regression please click [here](https://en.wikipedia.org/wiki/Linear_regression)<br>


<img src="https://github.com/Natan93100/SQL_Project_2024/blob/main/Scatter%20Chart.png" alt="Alt text" width="350" height="250"><br>

### C
### [Longest Continuous Sequence In Array](https://github.com/Natan93100/SQL_Project_2024/blob/main/Longest%20Sequence/main.c)

**Goal:**<br>
The goal of this C program is to find the longest sequence of continuous even numbers in an array.
The program identifies sequences where even numbers follow each other with a difference of 2 and outputs the longest such sequence.

**Logic:**<br>
The program iterates through the array and checks for even numbers.
If a number is even and the difference between it and the next number is exactly 2, it is considered part of the sequence.
The program keeps track of the length of each sequence.
The longest sequence is printed out, and if no sequence is found, it outputs a message indicating that.

**Edge Occurences:**
1. If no even sequence is found, the program prints "No even sequence in the array."
2. If only one even number is found, it prints the number.



