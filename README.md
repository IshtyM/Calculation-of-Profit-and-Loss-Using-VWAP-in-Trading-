# Calculation-of-Profit-and-Loss-Using-VWAP-in-Trading-

Volume weighted average price is known to be a versatile tool that is widely used by technical traders in finding good equities for investment. It is used by mutual fund portfolio managers when they have to buy a substantial number of a particular stock. Similarly, retail traders use VWAP to find the future potential of a stock, and intraday traders to determine the mean price in the market so they can buy a stock when the price is below VWAP.

It is a weighted average formula, which is widely used by analysts and traders alike to determine the demand for a stock both in terms of volume and price.

Attached data is the Bank Nifty time series data of 1 min. Intially Backtest is done using Python. Then the data is converted data into 15 min time frame. This is followed by Intraday trades are to be taken and mandatorily closed in the same day.
Trade starts only after 2nd 15-minute candle (9:30 to 9:45). This comes with condition, if candle closes above VWAP, we will buy and if candle closes below VWAP, we will sell
Example: If 2nd candle is closing above VWAP, we will buy 1 tick above candle high and Stop Loss (SL) will be 1 tick below candle low. If stop loss is not hit, then all trades are exited at 3:15 PM.
Aim is to calculate the overall profit and loss and to segregate the Profit and Loss Year wise and Day wise

### Libraries Used:
Pandas, Numpy, Matplotlib

### Programing Language
Python

### IDE Used
Jupyter Notebook
