# Hypothesis-Testing

#Objective
Practicing hypothesis testing using Python programming language. From the dataset given, hypothesis testing should be done to prove/test either education influencing income or not.

## Data and Data Source
This use case using data from https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis?resource=download

## Data Preparation
- The data consist of 29 columns/feature 
- There are missing values in "Income" feature, it is then filled with median of the "Income" feature.

## Data Processing
- After handling the missing data, the hypothesis should be state;
- H0: Education does not have significant effect to Income
- H1: Education does have significant effect to Income
- Level of confidence = 95% means alpha = 0.05
- Because there are several education level, means there are several population to be compared. In this case we use ANOVA Test

## Results
- P value = 1.075202108156874e-22
- Because p value < alpha, then there is enough evidence to reject Ho
- The decision is to reject Ho and accept H1:  Education does have significant effect to Income


