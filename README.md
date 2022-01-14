
# Electricity Demand Forecasting 

To ensure the better electric grid operation and utility resourse planning, accurate electric energy demand forecasting is necessary. To enhance the grid resilience and energy security, the demand forecast should account for the extreme weather events also. As the world understood the need for utilising the natural energy sources, PV and solar grid installation also should be considered for accurate forecasting. 

In this project, first, a simple Linear Regression model is considered as a baseline model, and then the model is improved by considering multi seasonality and lag values of energy used. Final model uses XGBoost algorithm and the corresponding performance measures are: 

* R2 score = 0.99
* RMSE = 47.44
* MAPE = 1.44 %

This demonstrate an improvement of 0.33 in R2 score, a decrease of 6.8 % in MAPE, and a decrease of 207.54 in RMSE value,  from the baseline model. 

**Data Description:** *To develop the Electricity demand forecasting model, this project uses the Energy consumption data of SanDiego for the years 2014 to 2018, and the corresponding weather data from San Diego Airport weather station and PV installation data of SanDiego for the corresponding years is used.*

**Assumptions:** *This project is done by assuming that, the PV installation data and weather data are available in future, without any forecasting requirement. But in real time, it is required to forecast these also. However, simply subsituting the values for weather and PV installation related variables, using the already forecasted values will ensure the performance of the model developed in this work.* 
