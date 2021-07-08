# SIMPLE LINEAR REGRESSION ANALYSIS

**Task 1:** 

Implementation of simple linear regression analysis.

![Simple_linear_Regression](https://user-images.githubusercontent.com/85668824/124931954-4cfa9d00-e020-11eb-98d2-053987cac5e4.gif)


## Problem Statement

<b>Predict the percentage of an student based on the numbers of study hours.</b>

## Dataset Name

student_scores - student_scores.csv

## Column Description

Independent Variable : **Hours** (Number of hours student has studied in a day)

Target Variable : **Scores** (Percentage of marks obtained by the student corresponding to the number of study hours he has studied)

## Table of Contents

1. Importing Libraries
2. Data understanding
3. Building a model
4. Evaluationg the model
5. Predicting the score if a student studies for 9.25 hrs/ day?


## EDA Summary

1. The dataset has records of 25 students and their scores correspondong to their number of study hours.
2. The target variable is a number and continous in nature. The first assumption of the Linear regression is satified.
3. There is no mistake in the datatype of the variables when compared to the probelm statement.
4. The student who has studied for the highest number of hours(9.2hrs) is not the topper(88 score).
5. The student who has studied for the least number of hours(1.1hrs) is the one with the lowest score(17).
7. There are no missing values of any kind(standard/non-standard) or duplicate records in the given dataset.
8. Both the variables are normally distributed and their skew values are closer to 0.
9. There are no outliers in any of the variables.
10. From the lmplot and heatmap,there is a linear relationship between the target and the independent variable.


## Predicting the score if a student studies for 9.25 hrs/ day?

No of Hours = 9.25

Predicted Score = 94.77111221192709
