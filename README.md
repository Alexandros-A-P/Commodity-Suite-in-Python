# Commodity-Suite-in-Python
A Repository with four different Jupyter lab files (2/4 currently complete). Ranging from data scraping via yfinance to analysing time series and assessing rolling correlations.

'PART1_getting_data_Closing' shows the reader how to scrape Commodity data (Closing prices) into Python and immediately save as CSV. This is the foundational step of the entire suite, as such, this should be read first.

If not viewable in github the link can be accesses here: 

https://github.com/Alexandros-A-P/Commodity-Suite-in-Python/blob/main/PART1_getting_data_Closing.ipynb

'PART2_Log_returns.ipynb'involves the next step which is to calculate log returns from Closing prices which is a useful step towards transforming financial data, this is followed by an ADF (Stationarity) test to assess the eligability of log return data as an approriate metric. Finally, some distributive properties can be explored before moving on to the next step, which is assessing volatility using the ARCH/GARCH family of models.

https://github.com/Alexandros-A-P/Commodity-Suite-in-Python/blob/main/PART2_Log_returns.ipynb

'PART3_TS_analysis', now that data has been (1) scrapped, (2) transformed into log returns and tested for Staionarity, the third addition to the project is to check the time series properties of the four commodities such as (but not exclusively): PACF & ACF for modelling series and ARCH/GARCH family of models for aeesssing volatility. 

Finally, rolling correlations on both weekly and monthly bases are run to investigate the association between different metals. 
