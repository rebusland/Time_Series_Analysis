# Time series analysis of SP500 returns
Time series analysis on market prices returns.  
The natural target was the SP500 index: redirecting the present
analysis towards a stock (e.g. a brisk one like Tesla) would probably lead to way more "funny" results.  
The input data in the selected time span are retrieved automatically from *Yahoo finance* through pandas_datareader.

## Outline
I bet you can walk through the Notebook without too much effort (comments are neat). Here, I recap the different kind
of analysis performed on the price returns:
 - Auto-Correlation Funcion (ACF) and Partial Auto-Correlation Funcion (PCF)
 - Discover Volatility Clustering, Heteroskedasticy using ACF/PCF and Ljung-Box test
 - Investigating stationarity: Augmented Dick-Fuller (ADF) test
 - ARIMA model
 - Capture Heteroskedasticy with a GARCH model and t-test
 - A focus around Black Monday (October 1987)

## Exploited libraries
 - matplotlib
 - numpy
 - pandas
 - scipy
 - statsmodel
 - arch
