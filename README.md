# AdEase-Time-Series
We understand the per page view report for different wikipedia pages for 550 days, and forecasted the number of views so that we can predict and optimize the ad placement for the clients. We are provided with the data of 145k wikipedia pages and daily view count for each of them.


Imported the dataset and doing usual exploratory analysis steps like checking the structure & characteristics of the dataset

Checked the null values and understanding their reason.

Understanding the page name format and splitting it to get different information.

Separated different values from it like title, language, access type, and access origin.

Visualized the data and getting inferences from them

Converted the data to a format that can be fed to the Arima model (Pivoting etc)

Checked if the data is stationary

Dickey-Fuller test

Tried different methods for stationarity.

Decomposition of series.

Differencing the series.

Plotting the ACF and PACF plots


Modeling : Created and training the Arima model, Getting the exogenous variable and using it to train a sarimax model, Used facebook prophet for forecasting

Finded a way to find the best params for my modeling approach.

Defined functions for all of the tasks.

The MAPE for previous batches has been in the range of 4-8%
