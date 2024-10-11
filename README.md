**Time Series Analysis**
A collection of data points taken at various periods of time is called a time series. 
Analysing time series data with a variety of statistical tools and methodologies is known as time series analysis. 
I use the Parking Birmingham time series dataset, which I acquired from the UCI machine learning library, to examine it for this research.

**Time series terminology**

Dependence- It refers to the association of two observations of the same variable at prior time periods.

Stationarity- It shows the mean value of the series that remains constant over the time period. If past effects accumulate and the values increase towards infinity then stationarity is not met.

Differencing- Differencing is used to make the series stationary and to control the auto-correlations. There may be some cases in time series analyses where we do not require differencing and over-differenced series can produce wrong estimates.

Specification - It may involve the testing of the linear or non-linear relationships of dependent variables by using time series models such as ARIMA models.


**Description of the dataset**

For this study, I have made use of the Parking Birmingham Data Set. The data set pertains to Birmingham, UK's parking situation. The data displays the car occupancy rates (8:00 to 16:30) for the months of October 4, 2016, and December 19, 2016. There are 35717 occurrences and 4 attributes in the data set.

**ARIMA Model**

ARIMA stands for AutoRegressive Integrated Moving Average. It is a generalization of an AutoRegressive Moving Average (ARMA) model. These models are fitted to time series data to better understand the data or to predict future points in the series called forecasting.

So, ARIMA models are denoted with the notation ARIMA(p, d, q). These three parameters account for seasonality, trend and noise in timeseries datasets.

**Fitting ARIMA model**

With GridSearch, I have found the ideal combination of parameters that yields the best-fitting model. I will now create a new SARIMAX model by fitting these ideal parameter values.

**Conclusion**

I use a seasonal ARIMA time series model in Python for this project in order to forecast the occupancy rates of the parking lots in the Parking Birmingham Data Set. According to the forecasts, the time series model is anticipated to keep growing steadily. We lose confidence in our values as we project farther into the future.
