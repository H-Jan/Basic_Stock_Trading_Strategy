# Basic_Stock_Trading_Strategy
This is a hypothetical stock trading algorithm based on historical data of selected stocks that places trades based on the crossover's of various simple moving averages

The requirements for this project was jupyter notebook, numpy, quandl (API), pandas, datetime, matplotlib, and mplfinance (using .original_flavor since mplfinance is deprecated and need to access candlestick_ohlc). The language used is Python. 

The first section is a simple visualization of the stock data using matplotlib package and DataFrame. From this we created a line chart of the price fluctuations acrosss a set amount of time under plot "Closing Price of Apple Stock"

Next step of order was to create a candlestick chart, a plot popular with trading that relays the opening, closing, high, low, variability, gain, and loss of a certain time period of trading.   
  The candlestick charts of AAPL, MSFT, and FB are included across the time period of 2015-01-11 to 2017-11-11

In comparing the 3 aforementioned stocks, we plotted their closing adjusted price to allow for direct comparison without visual variability due to their inherent numerical value. 

Next, we began looking into moving averages to better compare the best "buy/sell" opportunity using crossover events of 20 day, 50 day, and 200 day simple moving averages
  Using these crossover events, we created a historical window through which our algorithm would recommend a buy (green) for the stock and a neutral/sell (white)
  
In addition to our above algorithm, we used it against a backtest of previous data for multiple stocks to determine what our ideal "portfolio" of 1 million dollars would return across the aforementioned time period, resulting in a 40% gain when bought with the specific stocks across 2015-01-11 to 2017-11-11
