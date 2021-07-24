# Homework_10_TSA

### This project is completed for Fintech Bootcamp Fall 2021.
### Vincent Xin Wen

## Homework Background
The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies.
In this assignment, you will test the many time series tools that you have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.
You will gain proficiency in the following tasks:

1. Time series forecasting
2. Linear regression modelling

## Regression Analysis

first we used invitigated Seasonal Effects with Sklearn Linear Regression

**Question:** Does this model perform better or worse on out-of-sample data as compared to in-sample data?

**Answer:** The model performs better on out of sample data than the in sample data. As we can see the RMSE of out of sample is 0.6445 which is lower than the rmse of 0.8418 from in sample data.


## Time Series Analysis & Modelling with CAD-PHY Exchange rate data

**Question 1:** Based on your time series analysis, would you buy the yen now?

**Answer:** based on our analysis, the price will drop and the volatility will increase in the next 5 days, now is not the time of the buying yen.
    
**Question 2:**  Is the risk of the yen expected to increase or decrease?

**Answer:** with the price drop and volatility increase, the yen risk will increase.
   
**Question 3:** Based on the model evaluation, would you feel confident in using these models for trading?
**Answer:** the model used, arma and arima model results is providing a low CI and P Value, the model need some improvements.