# <ins>Automatidata Taxi Fare Prediction Project</ins>
<br></br>
## Project Overview 
Automatidata team to build a multiple linear regression model to predict taxi
fares using existing data that was collected by the team.Build a multiple linear regression model. In this scenario, the New York City Taxi and Limousine Commission (TLC) has approached the data consulting firm Automatidata to develop an app that enables TLC riders to estimate the taxi fares in advance of their ride.
## Objective 
The goal is to build a multiple linear regression model and evaluate the model. It includes:

1. Conduct a complete exploratory data analysis.
2. Perform any data cleaning and data analysis steps to understand unusual variables (e.g., outliers).
3. Use descriptive statistics to learn more about the data.
4. Create and run a regression model

 ## Data set 
 The data set has 22699 rows and 18 columns describe various features. 
 
 ## Exploratory Data Analytics 
As a result of the conducted exploratory data analysis, the Automatidata data team considered trip distance and total amount as key variables to depict a taxi cab ride. The provided scatter plot shows the relationship between the two variables. This scatter plot was created in Tableau to enhance the provided visualization.
![alt text](https://github.com/mayanktiwari-cpu/Data_science_project/blob/7ee4e9e07c1310122bdeb020849a530454b8374d/Automatidata%20Taxi%20Fare%20Prediction%20Project/Screenshot_2025-08-24-20-02-00-22_e2d5b3f32b79de1d45acd1fad96fbb0f.jpg)

## Feature Engineering 
° Create a new column `duration`,`mean_duration`,`mean_distance`,`rush_hour` and `day and month`.

° Isolate modeling variables.

° Identify correlations.

° Use StandardScaler() to standardize the variable 
## Model Training 

Develop a multiple regression model using  passenger_count, mean_distance, mean_duration, rush_hour, VendorID_2 to train the model as independent variables and take fare_amount as dependent variable .The test set should contain 20% of the total samples. Set random_state=0.
## Model Evaluation 

Evaluate the model performance by calculating the residual sum of squares and the explained variance score (R^2). Calculate the Mean Absolute Error, Mean Squared Error, and the Root Mean Squared Error.

|Model Performance |Train data |Test data |
|-----|-----|----|
|Coefficient of determination|0.8399|0.8682|
|R^2|0.8399|0.8682|
|MAE|2.1866|2.1336|
|MSE|17.8897|14.3264|
|RMSE|4.2296|3.7850|

## Results 
### Coefficients
|passenger_count | mean_distance| mean_duration |rush_hour | VendorID_2|
|----|----|----|----|----|
0 0.030825| 7.133867| 2.812115 |0.110233 |-0.054373

### Std. deviation : 3.5748

### Result interpretation:

For every 3.57 miles traveled, the fare increased by a mean of \$7.13. Or, reduced: for every 1 mile traveled, the fare increased by a mean of \$2.00.
## Impact 
The NYC Taxi and Limousine Commission (New York City
TLC), wants the Automatidata team to build a multiple linear regression model to predict taxi
fares .

- mean_duration and mean_distance are the best predictor for taxi fares with R^2: 86% indicating how well the model fits the data.
- rush_hour and passenger_count are also have affect the fare_amount but not much significant.
