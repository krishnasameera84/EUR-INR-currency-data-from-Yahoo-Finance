# EUR-INR-currency-data-from-Yahoo-Finance 
(ASSIGNMENT 2:)
To analyze EUR/INR historical currency data from January 1, 2023, to September 30, 2024
Scrape EUR/INR Data from Yahoo Finance:

Use libraries like yfinance in Python to retrieve data for the period from January 1, 2023, to September 30, 2024.
Calculate Technical Indicators:

For Moving Average (MA): Use a simple or exponential moving average over the specified periods (1-day and 1-week).
For Bollinger Bands: Calculate the bands using a 20-day moving average as the basis, with upper and lower bands at two standard deviations from the mean.
For Commodity Channel Index (CCI): Use a typical price (average of high, low, and close) over a specified period, subtracting the mean and normalizing by mean deviation.
Decision Based on Indicators:

Moving Average: If the currency rate is above the moving average, it might indicate a buy signal, while below may indicate a sell.
Bollinger Bands: Crossing the upper band can suggest overbought (sell), while crossing the lower band may suggest oversold (buy).
CCI: A high CCI might signal overbought, while a low CCI can signal oversold conditions.
