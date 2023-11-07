# pandas-challenge

### School Data Analysis Project

## Description
This data analysis project is focused on analyzing educational data from local government/indipendent schools.
And  aims to provide insights into school performance and student achievements.This project will help school board and mayor to make strategic decisions regarding future school budgets and priorities. 

This project used two datasets ,file schools_complete.csv which includes the following informations in columns Student ID,school_name,type,size,budget 
the file students_complete.csv ,which includes the columns Student ID,student_name,gender,grade,school_name,reading_scoreand math_score. For these analysis both datasets imported, merged, and the aggregate data diplayed in to python pandas dataframes. The project is conducted in Jupyter notebook.

##Observable Trends:

*The dataset encompasses a total of 15 schools, 39,170 students. The total students average maths score is 70.33 which is higher than the average reading score 69.98. When we see the passing rate maths (86.07%) has a higher rate than reading (84.42 % ),the overall passing rate is 72.80 %. These findings indicate that student's score more in maths than reading.

*The analysis of school spending summery shows,when the budget per student increases student's average math score, the average reading score, percent of passing math, percent of passing reading, and the overall passing decreases.

*The data revealed that when the number of students sizes higher in schools the average math scores, average reading scores, passing math, passing reading, and overall passing decrease. So, we can infer that, when student size rises, it negatively influences student achievement. Therefore, school board and government should work on student size in schools, and classes because it directly affects student achievement 
for so many reasons.


In conclusion, the School Data Analysis Project provides valuable insights into school performance and factors influencing student achievement. This analysis can inform decision-making and strategies for improving education outcomes.

## Project Structure
data folder contains:

- Resources: This directory contains the raw data files used in the analysis.
- PyCitySchool_starter.ipynb.: contains code 
- README.md: The file you are currently reading, providing an overview of the project.



## Table of Contents

   Prerequisites
   Local Government area Summary
   School Summary
   Top Performing Schools (By % Overall Passing)
   Bottom Performing Schools (By % Overall Passing)
   Math Scores by Grade
   Reading Scores by Grade
   Scores by School Spending
   Scores by School Size
   Scores by School Type

## Prerequisites

To produce this analysis, we will need the following tools and libraries:

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Matplotlib](https://matplotlib.org/)

The project involves several key analysis tasks, including:

1. **Local Government Area Summary**:
The dataset encompasses a total of 15 schools, 39,170 students. The total students average maths score is 70.33 which is higher than the average reading score 69.98. When we see the passing rate maths (86.07%) has a higher rate than reading (84.42 % ),the overall passing rate is 72.80 %. These findings indicate that student's score more in maths than reading.


2. **School Summary**:
this dataset contains School Name,School Type,Total Students,Total School Budget,Per Student Budget,Average Maths Score,Average Reading Score,% Passing Maths,% Passing Reading,% Overall Passing (The percentage of students that passed maths and reading.)
The school summary finding showed that from 15 schools 8 of them are independent schools , and the other 7 of them government schools. The number of students in schools ranged between 427 students (Holden High School) to 4976 students (Bailey High School).


3. **Highest-Performing Schools (by % Overall Passing)**: Identifies and displays the top 5 schools with the highest overall passing percentage



4. **Lowest-Performing Schools (by % Overall Passing)**: Identifies and displays the 5 schools with the lowest overall passing percentage.

5. **Math Scores by Year**: Calculates average math scores for students of each year level (9, 10, 11, 12) at each school.

6. **Reading Scores by Year**: Calculates average reading scores for students of each year level (9, 10, 11, 12) at each school.

7. **Scores by School Spending**: Breaks down school performance based on average spending ranges (per student) and calculates mean scores and passing percentages.
A table of Scores by School Spending looks as follows:



8. **Scores by School Size**: Breaks down school performance based on school size (small, medium, large) and calculates mean scores and passing percentages.

9. **Scores by School Type**: Analyzes school performance based on school type and calculates average scores and passing percentages.

## Results

The analysis results in various DataFrames containing important metrics, such as school summaries, performance by spending, performance by size, and performance by school type.



## About

-These projects were completed as part of 
Data Analysis Bootcamp.



## Contact
If there are any questions of concerns, I can be reached at:
##### [github: svuth23](https://github.com/svuth23)
##### [email: swapna.vuthpala@gmail.com](mailto:swapna




