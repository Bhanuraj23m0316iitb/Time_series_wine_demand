# Time series analysis for demand forecasting 

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhWApZWwMXe9_ymkjJSe_ciD8zUbCnnNbP8qYYknSi4hxd7TIqZ1JnAspLxQahgC-_44sclV-81Px5eYouEDlBZPfHfSrNOO3QcYQtLMkhKLkA6X4XAu3vYsa6HwD0f9W1nXt01Ru1nCfRAZ_Y1EvG_D_VfmRz0Q2Cnxyr1tK-ZjDv_VDomxUx4Bk-4-yk/s16000/clock_ts.png" height=300px>
</p>
<br/>

## About the project
This study aimed to create a machine-learning model to predict the demand for wines in a specialized store for this product. Pandas Profiling was used to generate a report that assisted in the exploratory data analysis. Additionally, feature engineering was applied, resulting in 9 new attributes. The Augmented Dickey-Fuller (ADF) test indicated that the series was non-stationary, and for this reason, the series was transformed into a stationary one using techniques such as applying a log transformation to reduce the magnitude of values, subtracting the 30-period moving average, and differencing. The forecasting was performed with a parameter of 120 days, and the following methods were used: Naive approach, Moving Average, Holt's Linear Trend Model, ARIMA, Prophet, and PyCaret. In the latter, 27 preliminary models were generated, from which the best one was selected to proceed with hyperparameter tuning and data forecasting.

As a result, according to the Mean Absolute Percentage Error (MAPE), the ARIMA model performed the best with an error rate of only 2.33%, followed by Prophet with 2.87% and Holt with 2.90%.
