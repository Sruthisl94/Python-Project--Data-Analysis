# Python-Project--Data-Analysis
## Objective: This project aims at comprehensive analysis of data from a company containing the detailed information of employees across various teams.
## Project Overview
* The dataset contain 458 rows and 9 columns including the features such as Name,Team,Number,Position,Age,Height,Weight,College and Salary.
* The dataset contain missing values in the Salary and College column and the Height column had inconsistent data and hence need imputation techniques for further analysis.

## Data cleaning and Imputation techniques
 To ensure data accuracy and consistency, the following steps were applied:

* Missing Values Handling:

Salary Column: Missing values in the Salary column were replaced with the mean salary.
College Column: Missing values in the College column were filled with the label "Unknown". 

Height Column Correction:
The Height column contained inconsistencies, which were addressed by replacing these values with random integers between 150 and 180 to approximate reasonable employee height values.

## Project Outcome:
After performing data cleaning and imputation, the dataset is now ready for further analysis, to derive meaningful insights.

## Tools required:
This  project has been done using python by importing the libraaries viz:
  (1) Pandas
  (2) Matplotlib
  (3) Numpy
  (4) Seaborn

> Results:
 * The distribution of employees in each team has been studied by plotting a bar plot and percentage split relative to the total number of employees was calculated. Each team consist of 3% or 4% of employees.
 * Pie Chart is plotted to visualize the segregation of employees based on their positions.
   22.3% of employees is having SF position.
* The conditional statements in python is used to find out the predominant age group and bar plot is used to visualize the frequency of employees in each age group. 235 employees belong to the age group 26-35.
* By pandas group by method, the team and position having the highest salary expenditure has been calculated and derive the insights that the team 'Los Angeles Lakers' with postion 'SF' have the highest salary expenditure with an amount of $31866445.0
* The correlation between age and salary has been find out by calculating correlation matrix and visually shown by plotting the heat map.
* The correlation of 0.21 for age and salary suggest that there is a weak positive correlation between the two variables.

