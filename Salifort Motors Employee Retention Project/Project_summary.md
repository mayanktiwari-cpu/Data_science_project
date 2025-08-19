# Salifort Motors Employee Retention Project

## Introduction 

Salifort Motor seeks to improve employee retention and design a model that predicts whether an employee will leave the company based on their satisfaction_level , department, number of projects, average monthly hours and others factor.

## Business Scenario

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They have collected data from employees and wants to provide data-driven
suggestions based on your understanding of the data.

## Problem and objectives

The HR department collected data from employees on different heads and wants to find the answer of "what’s
likely to make the employee leave the company?". The goal of this project are to analyze the data collected by the HR department and to build a
model that predicts whether or not an employee will leave the company and identify factors that contribute
to their leaving.

## Dataset 
The dataset contains 15,000 rows and 10 columns .

## Exploratory Data Analysis 

- Understand your variables
- Clean dataset (drop duplicates and missing value) and rename colums
- Check for outliers in the data
  ![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/caa928276d8e512fe10f068f44806131ee2789bf/Salifort%20Motors%20Employee%20Retention%20Project/Screenshot_2025-08-19-08-21-04-93_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)
**Visualize distribution of `tenure` and detect outlier.**
## Data visualizations 
Create plots to visualize relationships between different 
variables in the data.
![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/4a52689dce12f0752ec712763dcb3deb8bcf6fa7/Salifort%20Motors%20Employee%20Retention%20Project/Screenshot_2025-08-19-09-51-33-30_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)
**Box plot and Histogram to understand the relationship between average_monthly_hours and number_project.**
![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/8e6f93a91f0b0038ab60aec8fbccf75f88152627/Salifort%20Motors%20Employee%20Retention%20Project/Screenshot_2025-08-19-10-06-24-73_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)
**Scatter plot to demonstrate the effect of average_monthly_hours on satisfaction_level.**
![alt](https://github.com/mayanktiwari-cpu/Data_science_project/blob/6ca0c15cbc015570a0361bf8b7d1ac1345b0a727/Salifort%20Motors%20Employee%20Retention%20Project/Screenshot_2025-08-19-12-43-25-25_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)
**Heatmap that shows the correlation between the different features.**

## Model Development
Applied multiple models to find the best suitable.
- Logistic Regression with 82% score.
- Decision Tree with 97.43% score.
- Random Forest with 98.18% score.
- XGBoost with 98.35% score.
## Results & Insights:
- <ins>Best Model:</ins> XGBoost achieved 98.35% accuracy .
<br></br>
- satisfaction_level, number_project, tenure, last_evaluation, average_monthly_hours are the important features with high gini importance to predict employee retention.
![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/cc14d87ce2d2ca657e000240047a40e9bdfbb0cd/Salifort%20Motors%20Employee%20Retention%20Project/Screenshot_2025-08-19-22-11-27-40_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)
- More than 4 project and 250 monthly hours the employee most likely to left.

## Impact:

The model enables the HR Department to identify the employee who is likely to left because it is time-consuming and expensive to find, interview, and hire new
employees, increasing employee retention will be beneficial to the company.
