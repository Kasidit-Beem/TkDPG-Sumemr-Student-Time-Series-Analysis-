# List of Model

## 1. ARIMA model

ARIMA model is the most widely used time series forecasting model. It is acronym for AutoRegressive Integrated Moving Average 

1. AR : Linear combinations of the past values of the variable
2. MA : Linear combinations of the past forecast error
3. I : Differencing 

where there're parameters descripting the model p, d, q which is order of the AR part, degree of first differencing involved, and order of the MA part, resepctively.
    

#### Descriptive Detail 
1. [Forecasting: Principles and Practice (Chapter 8)](https://otexts.com/fpp2/arima.html)

#### Example
1. [Time Seies Analysis using ARIMA FROM Statsmodels](https://www.nbshare.io/notebook/136553745/Time-Series-Analysis-Using-ARIMA-From-StatsModels/)
2. [How to Create an ARIMA Model for Time Series Forecasting in Python](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/)
3. [Introduction to Regression With ARIMA Errors Model](https://timeseriesreasoning.com/contents/regression-with-arima-errors-model/) 

#### ARIMA statsmodels
we use statsmodels [**```version 0.10.2```**](https://www.statsmodels.org/v0.10.2/generated/statsmodels.tsa.arima_model.ARIMA.predict.html#statsmodels.tsa.arima_model.ARIMA.predict)