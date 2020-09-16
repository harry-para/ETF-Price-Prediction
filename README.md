# ETF-Price-Prediction
This project used ETF data that was sourced from Yahoo Finance using an API. Time series data was collected from 2015 to the present day.

The purpose of this project was to use the existing time series data to predict the ETF prices for a specified timeframe, such as the next couple days.

This analysis used feature enginneering to produce more insights based on the data such as home and vistor team win streak, if the home team or visitor team won their last game and if the home team won against a specific team the last team they played. Team names were also encoded to ensure they could be used as variables for prediction.

This analysis did a 70% training data and 30$ testing data split using an ARIMA model for price prediction.
Forecast error statistics were also calculated to compare the model to the actual prices.

This analysis used Google Sheets to store the NHL regular season data and pandas dataframes online that were later used to produce data visualizations on Tableau. The Tableau workbook uses the Python programming language via TabPy to give a more visual representation by comparing the chosen classification algorithm's performance to the actual results of the games. TabPy is an API that enables evaluation of Python code from within a Tableau workbook. The link to the Tableau workbook is:

The Python script and output using Jupyter Notebooks via the Visual Studio Code editor is attached above as "NHL Win Prediction.ipynb".
