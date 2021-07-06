# Time series analysis with Japanese Yen
---

This repository contains iplementation of various time series linear analysis with historical futures price data of Japanase Yen versus U.S. Dollar. 

This gives ideas about how to use following timeseries techniques using Pythin's statsmodels library 
* Timeseries decomposition to noise and trend using Hodrick-Prescott Filter
* Forecasting using ARMA model
* Forecasting using ARIMA model and 
* Volatility forecasting usinf GARCH model

Same timeseries data has been used to implement a simple linear Rgression model with Scikit-learn library



## How to run the notebooks <br>
Clone the entire _"timeseries-analysis-japanese-yen"_ repository into a local folder by issuing the following command from gitbash <br>
```
$git clone https://github.com/Roy-Tapas/timeseries-analysis-japanese-yen.git
```
Stay in the same gitbash directory and open Jupyter lab by issuing the following command from gitbash: <br>
```
$Jupyter lab
```

Implementations are in following two notebooks:
* time_series_analysis.ipynb
* regression_analysis.ipynb

## Important points to note 
Retain the folder structure as cloned from github.  
Hierarchy inside timeseries-analysis-japanese-yen should look like the following:
```
timeseries-analysis-japanese-yen 
        |---------------> README.md 
        |---------------> time_series_analysis.ipynb 
        |---------------> regression_analysis.ipynb 
        |---------------> yen.csv
                        
```



<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** rtapask@gmail.com