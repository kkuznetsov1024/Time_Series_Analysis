# Time_Series_Analysis
Data set:
The set was taken from quandl and consist of 1478 entries of the exchange rates of XRP to BTC. Each day’s last value of the day was taken for this analysis.

Objective:
Build a prediction model for the relationship between XRP and BTC prices.

Process:
ARIMA model was chosen for this analysis.
Looking at the decomposition, data did not show any noise or seasonality. Trend is the only factor that contributed to the patterns. Testing the stationarity, it was found the data was not stationary, so a single iteration of the difference method was applied before building the ARIMA model.
Different values of parameters p and q were taking into consideration and accuracy rate was studied.

Solution:
ARIMA model showed very low mae and rmse, therefore the model can be applied for further analysis
