# Commodity-Suite-in-Python
A Repository with four different Jupyter lab files. Ranging from data scraping via yfinance to analysing time series and assessing rolling correlations.

'PART1_getting_data_Closing' shows the reader how to scrape Commodity data (Closing prices) into Python and immediately save as CSV. This is the foundational step of the entire suite, as such, this should be read first.

If not viewable in github the link can be accesses here: 

https://github.com/Alexandros-A-P/Commodity-Suite-in-Python/blob/main/PART1_getting_data_Closing.ipynb

The next step is to calculate log returns from Closing prices which is a useful step towards transforming financial data followed by ADF (Stationarity) testing to assess the eligability of log return data as an approriate metric. Finally, some distributive properties can be explored before moving on to the next step, which is assessing VaR using historic and paramteric methods.

https://github.com/Alexandros-A-P/Commodity-Suite-in-Python/blob/main/PART2_Log_returns.ipynb

Forecasting with ARIMA may also be carried-out although ADF tests must be done first to ensure stationarity. Then Volatility can be assessed by using the ARCH and GARCH 
family of models to investigate volatility clustering and asymmetry. 

Finally, rolling correlations on both weekly and monthly bases are run to investigate the association between different metals. 
