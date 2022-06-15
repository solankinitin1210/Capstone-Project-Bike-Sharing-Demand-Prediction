# Capstone Project : Bike Sharing Demand Prediction
## Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
## Attribute Information:
• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours
## Conclusions:
- Multiple regressors were compared and evaluated with Adj_R2 and RMSE scores. With the best model, Bagging achieved an accuracy of 86% and RMSE of 234, which indicates that machine learning indeed can predict bike counts required for a stable supply of rental bikes
- The Bagging regressor performed the best out of 7 traditional models on the data set. Which has produced the highest accuracy of Adj_R2 of 86%. The reason why this algorithm produced good results is that Bagging decreases variance, not bias, and solves over-fitting issues in a model. 
- The feature temperature accounts for the highest importance therefore people of Seoul are more likely to stay home during colder days than on warmer ones. Depending on the feature importance of temperature and study on people activity associated with whether the temperature is the most important factor when it comes to sharing bikes.
