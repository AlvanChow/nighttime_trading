# Night Time Trading Phenomenom - Stock Analysis

I came across an article that stated night-time or after-hours trading accounted for most of a stock's gains over time.

```
If you had bought the SPY at the last second of trading on each business day since 1993 
and sold at the market open the next day — capturing all of the net after-hour gains — 
your cumulative price gain would be 571 percent.

On the other hand, if you had done the reverse, buying the E.T.F. at the first second of
regular trading every morning at 9:30 a.m. and selling at the 4 p.m. close, you would be 
down 4.4 percent since 1993.

Source: https://www.nytimes.com/2018/02/02/your-money/stock-market-after-hours-trading.html
```

Many finance gurus advise against day trading or timing the market, so this finding seemed quite extraordinary.

Using Python (Pandas, Numpy, Matplotlib), I conducted some further analysis on AAPL and MU to see if this held true for single stocks as well.

If you used this strategy for AAPL, your cumulative price gain would be 171% in 10 years. Whereas if you 
did the reverse, you would be down 11.7%.

![Alt text](/AAPL.png "AAPL")

If you used this strategy for MU, your cumulative price gain would be 83% in 10 years. Whereas if you 
did the reverse, you would be down 30.7%.

![Alt text](/MU.png "MU")

It's a very very interesting and potentially fruitful pattern, but ultimately I believe it is infeasible because brokerage fees would be too expensive and eat away at your returns.
There is opportunity to look into this finding more.



