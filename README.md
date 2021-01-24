# School_District_Analysis
 Programming Language Used: Pandas Python

## Overview of Project

### Purpose
A school board hired a consulting firm to analyze due to academic dishonesty which was suspected. 
students_complete.csv shows evidence of reading and math grades for Thomas High School ninth graders appears to have been altered. The school board does not know the full extent of the academic dishonesty , and in order to uphold state testing standard, they have hired this firm for help.

The analysis conducted compares previous school district analysis against this firm's analysis in order to determine how the suspected academic dishonesty affects school performance.

The school board has requested the following deliverables:

A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size
School performance based on the type of school

### Results
Thomas High School Scores
Math and reading scores for ninth graders at Thomas High School were replaced with 'NaN' (Not a Number) so that their scores would not affect future calculations. If all of the students' scores were replaced with a 'O', then this would negatively impact averages for the school and school district.

Thomas High School math scores:
Ninth grade math scores were replaced with NaN. Thomas High School 10th, 11th, and 12th grade math scores are as follows: 83.1, 83.5, and 83.5.

Thomas High School reading scores:
Ninth grade math scores were replaced with NaN. Thomas High School 10th, 11th, and 12th grade reading scores are as follows: 84.3, 83.6, and 83.8.

Scores by School Spending
District spending per school was calculated by determining average spending ($620), standard deviation (~30), minimum spending amount ($578), lower quartile ($592), mid quartile ($628), upper quartile ($642), and mximum spending amount ($655) across all 15 schools: 

### Summary
Removing 9th grade student scores from Thomas High School affected the school district in the following ways:

Average math scores dropped slightly (<1%)
Average reading scores were not affected
Percentage of students passing math dropped slightly (-1%)
Percentage of students passing reading dropped slightle (-1%)
The overall passing rate dropped (-1%)
Only scores for Thomas High School were affected:

Perentage of students passing math dropped from 93.2% to 66.9%
Percentage of students passing reading dropped from 97.3% to 69.7%
Overall passing percentage dropped from 90.9% to 65.1%
Thomas High School affected school rankings in the following ways:

Thomas High school dropped out of the top 5 high schools in the district
Wright High School moved into the top 5 high schools in the district
Bottom 5 high schools was unaffected
Removing 9th grade student scores from Thomas High School affected other reports:

Math and reading scores by grade remained the same for all other schools
Thomas High School had no data to report for 9th grade math and reading scores
Scores by school spending chaged at the $601-650 range:
Percentage passing math dropped from 73% to 67%
Percentage passing reading dropped from 84% to 77%
Overall passing percentage dropped from 63% to 56%
Scores by school size changed for medium-sized schools (1000-2000):
Percentage passing math dropped from 94% to 85%
Percentage passing reading dropped from 97% to 91%
Overall passing percentage dropped from 91% to 85%
Scores by schools type were affected in the following ways:
Percentage passing math dropped from 94% to 90%
Percentage passing reading dropped from 97% to 93%
Overall passing percentage dropped from 90% to 87%




