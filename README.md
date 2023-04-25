# corporate_revenue_forecast
Completed for DSA301 Time Series Analysis, in a group of 6, we model and forecast industry aggregated corporate revenues. 

We extracted the corporate revenue data for Russell 1000 companies from COMPUSTAT and using their GICS codes, aggregated them by industry. Then we utilised various time series modelling techniques including STL decompsition, SARIMAX, VAR and VECM models to forecast future values of the time series. In the end, we used out-of-sample statistics to compare the performance of the different models. While creating the models, we test relevant assumptions regarding stationarity, cointegration and autocorrelation among the data and the produced residuals. 

The repository contains our final report, my Python code to process and aggregate the Russell 1000 corporate revenue date and my R code to model the Healthcare sector and create a VAR model for all sectors' corporate revenues.
