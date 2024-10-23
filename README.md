
## Project tile - Yulu Bike Sharing Demand Prediction

### <b>Description:</b> 
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by [Alma Better](https://www.almabetter.com/).

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Business Context :</b>

In the evolving landscape of urban mobility, companies like Yulu Bike are at the forefront of providing efficient and eco-friendly transportation solutions. Accurate prediction of bike-sharing demand is crucial for optimizing fleet management, enhancing customer satisfaction, and maximizing operational efficiency. By analyzing data related to bike-sharing demand, Yulu Bike aims to gain a deeper understanding of the factors influencing bike rentals. The dataset includes a range of variables such as weather conditions, time of day, and special events, which impact bike usage patterns..

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

