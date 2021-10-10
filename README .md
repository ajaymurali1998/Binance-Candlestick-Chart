
# Binance CandleStick Chart

## Aim: 
To make an interactive candlestick chart using Plotly to know about the price of Ethereum 
     in Bitcoins(BTC) over a month.

## Description:
At first the to plot the data we acquired the data for 30 days ago using Python-binance. The data acquired is in the form of CandleStick data.

We convert the Timestamps into Datetime using Pandas and save the data frame as Csv file.

Next step we would use plotly to make the CandleStick chart from the dataframe  with X axis as 'dates' and Y axis as 'Ethereum Price in Bitcoins(ETHBTC)'.

We would also use 5 Day Moving average Scattered plot to undertand more about data.

Implementation and Step by step description are available at notebook [Binance_api.ipynb](https://github.com/ajaymurali1998/Binance-Candlestick-Chart/blob/main/Binance_api.ipynb)

## CandleStick Chart Basics

- When the real body is filled with red, it means the close was lower than the open. If the real body is green, it means the close was higher than the open.
- If the upper shadow on a down candle is short, it indicates that the open that day was near the high of the day. A short upper shadow on an up day dictates that the close was near the high.
- There are two Patterns in CandleStick which are bullish and bearish. Bullish patterns indicate that the price is likely to rise, while bearish patterns indicate that the price is likely to fall.
- Different Patterns are again divided as:
   - Bearish Engulfing Pattern
   - Bullish Engulfing Pattern
   - Bearish Evening Star
   - Bearish Harami
   - Bullish Harami
   - Bearish Harami Cross
   - Bullish Harami Cross
   - Bullish Rising Three
   - Bearish Falling Three
## Requirements

 - python_binance
 - pandas
 - plotly




## Candlestick Interactive Chart 

You can view the interactive chart on [fig.html](https://github.com/ajaymurali1998/Binance-Candlestick-Chart/blob/main/fig.html)

Since it is raw code you can use https://htmlpreview.github.io/ to view the Html pages.

To view the Static Chart Image visit [CandleStick Chart.png](https://github.com/ajaymurali1998/Binance-Candlestick-Chart/blob/main/CandleStick%20Chart.png)## CandleStick Chart Color Reference

| Color             | Meaning                                                             |
| ----------------- | ------------------------------------------------------------------ |
| Red | ![#b40300](https://via.placeholder.com/10/b40300?text=+) represents a Down Candle|
| Green | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) represents an Up Candle |


## Analysis Of CandleStick Chart

- Bearish Evening Star : Between sep 16,sep 17 and oct3 and oct4.
                   In subsequent we can see more selling had happened.
- Bearish Harami : Between sep 26,sep 27 and oct2 and oct3. It is not of much a pattern
                   but the prices had been decreased shows indecision on the part of the buyers.
- Bullish Harami : Between sep 28 and sep 29 . It This tells that the trend is pausing. If it is followed by another up day, more upside could be forthcoming .    
- The main conclusion is that after observing the moving average and candlestick the price of 
  Ethereum is decreasing with respect to Bitcoins for the month.             
## Acknowledgements

 - [Python-Binance](https://python-binance.readthedocs.io/en/latest/)
 - [Plotly CandleStick Charts](https://plotly.com/python/candlestick-charts/)
 - [Binance documentation](https://binance-docs.github.io/apidocs/spot/en/#compressed-aggregate-trades-list)

  
## Appendix

Prior Knowledge in Binance and Candlestick Chart will be more helpfull. 

  