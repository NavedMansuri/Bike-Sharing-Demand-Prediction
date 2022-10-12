# Bike-Sharing-Demand-Prediction

![Bike-Sharing-Demand-1194x501](https://user-images.githubusercontent.com/75332345/193004955-bb6e53ee-8a62-4a58-93ea-8a00f2e279c3.jpg)



# Project Title : Seoul Bike Sharing Demand Prediction

Problem Description
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Data Description

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

# Attribute Information:  
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


# EDA Summary
Dependent variable is positively skewed.  
The number of bikes rented is on average higher during the rush hours.  
Rented bike counts is higher during the summer and lowest during the winter.  
Bike count is higher on working days than on non-working days.  
Temperature has the highest correlation with the dependent variable.  

#   ML Model

![comp](https://user-images.githubusercontent.com/75332345/195401000-273a6987-fd29-4527-ace9-ce1a219534ba.png)  


![ml table](https://user-images.githubusercontent.com/75332345/195401419-656ea366-8231-40dc-b9cc-56921bd00619.png)










#   Conclusions
holiday or non-working days there is less bike demand.​

high demand at morning 8am and evening 6pm.​

clear visibility and low solar radiation is increasing bike demand.​

Gradient boosting R2 score is 99% and random forest R2 score is 98%.​

random forest and gradient boosting best model that can be used for the bike demand predication because performance matrix R2 and adjusted_R2 is higher.​

so result is best machine learning model for bike ranted prediction we use gradient boosting or random forest model.
