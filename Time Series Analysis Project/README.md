# Time Series Analysis Project

This was one of my favorite TripleTen projects. I was tasked with short-term forecasting for a taxi company using historical time series data.

## The Process

This project would certainly have a number of steps. I would first need to create the time index for my dataframe and resample it to every hour. Next, I would check for seasonality and any other trends I could find from the data. As is necessray for time series model, I would create new features that would implement lagging rolling averages and simple one day and one week lags. Many models would be trained, including an autoregressive model, linear regression, ARIMA, random forest, and gradient boosting (LightGBM). In the end, our LightGBM and random forest models met our RMSE criteria and also looked great when comparing the visualizations of actual orders versus predicted orders.

Please open the attached Jupyter Notebook to see how I reached my final results.
