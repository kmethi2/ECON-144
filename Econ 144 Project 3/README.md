# Project 3
**Description:** For this last project, there wasn't any requirements, the objective was to use many different models to forecast a time series and compare which ones had the most success. For our dataset, we used monthly imports for the state of Georgia. 

## Models used
* Arima
* ETS model with a Box Cox transformation
* Holt Winters additive and multiplicative model
* Neural Network Autoregression model
* Prophet
* Combination Forecast

* Through all of these models, their accuracy were assessed based on a training testing split, with the test region being the last 5 years of the dataset. The diagnostic statistics used were the mean absolute error, root mean squared error, and the mean error. We also assessed the validity of each model by checking the residuals, and looking at the cusum plot.
  
* In the end, we compared these models based on the 3 diagnostic test statistics to pick the overall optimal model for the data
