
# Project tile - Seoul Bike Sharing Demand Prediction

**Description:**

This is a supervised ML (regression) capstone project on bike sharing demand prediction given by Alma Better.

**Problem statement:**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

**Dataset description :**
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

**Attribute Information:**

Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


**Project Flowchart:**
1.Initial preparations(Loading the dependencies and the data)

EDA

2.Clean-Up

Handling null values
Handling duplicate values
Removing Outliers

3.Feature engineering

Feature encoding
Checking correlation for feature removal
Removing Multicollinearity
Obtaining correlation between dependent and independent variables

4.Pre processing of the data

Target feature conditioning
Creating train and test dataset
Feature Scaling

5.Model implementation

Linear Regression
Ridge Regresression
Random forest Regression


Conclusion :

Most number of bikes are rented in the Summer season and the lowest in the winter seaso

We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day

Over 96% of the bikes are rented on days that are considered as No Holiday.

Majority of the bikes are rented for a humidity percentage range of 30 to 70.

Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.

Random Forest Regression is the best performing model with an r2 score of 0.7495.
Lasso Regression(L1 regularization) is the worst performing model with an r2 score of 0.4335.
