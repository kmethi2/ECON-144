# Project 2
**Description:** This project was a bit more complex, where we examined two time series datasets, analyzing the individual series, but also the relationship between the two. The data we used were monthly imports for two states, Georgia and New Jersey. 

  * First, we looked at the datasets individually. We first fit a TSLM model for the trend and seasonality and added an arima model for the cycles of the data, and forecasted the data with this model. 
  * Next, we fit an arima model itself as a full model
  * Lastly, we fit a VAR model to attempt to capture any dynamics between the two time series.
  * Overall, we used many metrics to compare these models such as MAPE/RMSE diagnostic statistics. We also looked at the IRF and Granger Causality tests to further examine any shared dynamics. 
