# Stock-Price-Analysis
This project used stock data that was sourced from Yahoo Finance using an API. Time series data was collected from 2015 to the present day.

The purpose of this project was to use the existing time series data to predict a specified stock's prices for a specified timeframe, such as the next couple days.

This analysis did a 70% training data and 30% testing data split and developed an ARIMA model for price prediction.
Forecast error statistics were also calculated to compare the model to the actual prices.
The ARIMA model was also used to forecast the stock price for the next couple days as displayed by the chart visualizations.

The R script using the RStudio editor is attached above as "ETF Price Prediction.Rmd".
To see the R script along with the output please click the link: file:///C:/Users/Vijaya/Documents/Python%20Projects/ETF%20Price%20Prediction/ETF-Price-Prediction.html

R packages used include tidyverse, tidyquant, ggplot2, MASS, tseries, forecast and zoo. 
