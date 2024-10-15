
## Project tile - Yelu Bike Sharing Demand Prediction

### <b>Description:</b> 
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by [Alma Better](https://www.almabetter.com/).

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Problem statement:</b>
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

#### <b>Note:</b> Dataset is provided by the company, Alma Better.

### <b>Dataset description:</b> 
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:
* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Project Flowchart:</b>
1. Initial preparations(Loading the dependencies and the data)

2. EDA 

3. Clean-Up
     * Handling null values
     * Handling duplicate values
     * Removing Outliers

4. Feature engineering
     * Feature encoding
     * Checking correlation for feature removal
     * Removing Multicollinearity
     * Obtaining correlation between dependent and independent variables
     
5. Pre processing of the data
     * Target feature conditioning
     * Creating train and test dataset
     * Feature Scaling
    
6. Model implementation 
     * Linear Regression
     * Ridge Regression
     * Lasso Regression
     * Elastic Net Regression
     * Random forest regression


![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Conclusion:</b>

1. EDA insights:
     * Most number of bikes are rented in the Summer season and the lowest in the winter season.
     * Over 96% of the bikes are rented on days that are considered as No Holiday.
     * Most number of bikes are rented in the temperature range of 15 degrees to 30 degrees.
     * Most number of bikes are rented when there is no snowfall or rainfall.
     * Majority of the bikes are rented for a humidity percentage range of 30 to 70.
     * The highest number of bike rentals have been done in the 18th hour, i.e 6pm, and lowest in the 4th hour, i.e 4am.
     * Most of the bike rentals have been made when there is high visibility.

2. Results from ML models:
     * Random Forest Regression is the best performing model with an r2 score of 0.495.
     * Lasso Regression(L1 regularization) is the worst performing model with an r2 score of 0.4335.
       
  
     
   


![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

