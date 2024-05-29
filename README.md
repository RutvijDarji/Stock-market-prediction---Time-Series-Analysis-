# Stock-market-prediction -Time-Series-Analysis
Stock price prediction is the process of forecasting the future movements of a company's stock 
based on historical data, market analysis, and various statistical models. Investors and traders use 
stock price predictions to make informed decisions about buying or selling stocks, managing their 
portfolios, and maximizing returns. This practice is a crucial aspect of financial markets and has 
gained increased attention with advancements in technology and the availability of vast amounts 
of financial data.
# Goal of project
This study addresses the problem of accurate stock price prediction 
for five major companies—Apple, Google, Microsoft, Tesla, and Amazon—using machine learning 
techniques. Financial markets generate vast amounts of data, including historical stock prices, trading 
volumes, economic indicators, and news sentiment. The objective is to preprocess and integrate diverse 
datasets to create a comprehensive input for machine learning models.
# Data Extraction and Web Scrapping
The data extraction from yfinance involves specifying the stock symbols, setting the desired 
time period for historical data, and calling the appropriate functions provided by the library. For 
example, to extract historical stock prices, the yfinance.Ticker class allows users to retrieve 
historical data using the history method. This method can be configured with parameters such 
as start and end dates, frequency (daily, weekly, etc.), and adjustments for dividends or stock 
splits.
# Reserach Questions
* How effective can time series forecasting techniques (like ARIMA, LSTM) be applied to predict stock prices based on historical data patterns?
* How do specific events (e.g., earnings reports, mergers, geopolitical events) impact stock prices, and can machine learning models effectively incorporate such events for better predictions?
# Libraries
* pandas
* Numpy
* sklearn
* statsmodels
* pmdarima
* seaborn
* matplotlib
* keras
* tensorflow
# Statistical Approaches
* Resampling time series data - month/quarter/year wise
* Augmented Dickey-Fuller test (ADF Test) - to Check Stationarity in Time Series
* SMA - Simple Moving Average
# Time Series Model
* Auto ARIMA 
* ARIMA - Autoregressive integrated moving average
# Deep learning Sequential neural network
* LSTM (Long Short-Term Memory) is a recurrent neural network (RNN) architecture with activation function like RELU and Tanh.
# ML Algorithms
* Simple Linear Regression 

