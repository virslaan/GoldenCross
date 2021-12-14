**EDAV Final Project Assignment**

Final Project Group: Zhaoyu Wu Vipul Harihar, and Zhirui Yang

**Introduction**

There is a wide variety of ways to generate profits in stock markets. Almost everyone knows how to make a profit from a trade: buy low, sell high. But the true million-dollar questions here are tricky: how do you know the stock price is low enough for you to buy? how do you know the price is high enough for you to sell? How do you determine the timing of the trade? The perfect solutions to these questions might not even exist or at least not widely known, otherwise, most of the people would become millionaires. However, some strategies take the advantage of the power of statistics and data visualization. These strategies do not necessarily guarantee the profits, but they surely do point the direction to the profits based on statistics and probability. One of these strategies is Golden Cross. But before we get into that, let's review some basics: 

***Why ‘Stocks’ ? What is ‘Stock Exchange’?***
A stock or the term share is usually used in representing a company's equity. We may understand
it as a financial instrument that assists in showing ownership in a corporation or a company and it
represents a proportionate claim on its assets (what it owns) and earnings (what it generates in
profits).
When we think of the term share stock exchanges, it is the secondary market, where existing
owners of shares can transact these shares of their equities with potential buyers.
It is important to comprehend that the corporations on stock markets do not buy and sell their own
shares on a regular basis (companies may engage in stock buybacks or issue new shares, but these
are not day-to-day operations and often occur outside of the framework of an exchange).
So we may sum it as whenever you buy a share of stock on the stock market, you are not buying
the stock directly from the company, you are buying it from another existing shareholder.
Likewise, when you want to sell the shares you own , they are not sold to the company—rather
you sell them to some other investors.

Project Problem Statement
There are numerous people in the market who want to invest in the stock market are way too afraid
to put their life’s savings at stake. Many people pour their life savings and dump their 401K
(contribution retirement plan) into the stock and option market. They perform various strategies
and financial maneuvers, hoping to gain massive profits but generally end up losing most of their
investments or still having underperformance in the general market.
Thus, our team started thinking if there is an investing strategy that can consistently beat the index
fund return.

**What is Golden Cross and how does it work?**
A golden cross is a chart pattern in which a relatively short-term moving average crosses above a long-term moving average. The golden cross is a bullish breakout pattern formed from a crossover involving a security's short-term moving average (such as the 15-day moving average) breaking above its long-term moving average (such as the 50-day moving average) or resistance level. 

There are three stages to a golden cross. The first stage requires that a downtrend eventually bottoms out as selling is depleted. In the second stage, the short term moving average cross the long term moving average, triggering a breakout and confirmation of trend reversal. The moving averages act as support levels on pullbacks until they crossover back down at which point a death cross may form. The death cross is the opposite of the golden cross as the shorter moving average forms a crossover down through the longer moving average.

With a bellwether index, the motto «A rising tide lifts all boats» applies when a golden cross forms as the buying resonates throughout the index components and sectors. Day traders commonly use smaller time periods like the 5-period and 15-period moving averages to trade intra-day golden cross breakouts. The larger the chart time frame, the stronger and lasting the golden cross breakout tends to be.

**The Difference Between a Golden Cross and a Death Cross**

A golden cross indicates a long-term bull market going forward, while a death cross signals a long-term bear market. The golden cross occurs when a short-term moving average crosses over a major long-term moving average to the upside and is interpreted by analysts and traders as signaling a definitive upward turn in a market.

**Limitations of Using the Golden Cross**

Golden Cross does not necessarily guarantee the profits due to the voliatility of the stock market. But they do show insights into the direction of price changes of the underling assets. Therefore, a golden cross should always be confirmed with other signals and indicators before putting on a trade, such as RSI and MACD.

**What Does a Golden Cross Indicate?**

A golden cross suggests a long-term bull market going forward.

Are Golden Crosses Reliable Indicators?

Traders often use a golden cross as confirmation of a trend or signal in combination with other indicators.


***How are we going to Proceed?***
1. Data Sources- data has to be historical
2. Data Collection from valid resources
3. Using Accurate metrics to define our problem questions
4. Plotting exploratory data analytics visuals, including CAGR (componded annual growth rate) and bootstrap simulation


***EDAV Final Project Assignment 4***
• Data Cleaning and Exploration
• Report writing and visuals finalization
• Study on the paper published by Barclay Equity Research: Impact of Retail Options
Trading

***Current Questions under study:
We are primarily focusing on these questions mentioned below:***
1. Data Investigation and checking if ‘Golden Cross’ exists.
2. Examination from a pure data perspective, using the visualization techniques to
demonstrate profit generated by Golden Cross investment method.
3. Calculation of the golden cross
Data Source and its availability:
We have a variety of data sources available to us. But as we are aware of this data being so valuable
we couldn’t get it for free thus on digging up deep, we found the Yahoo Finance Website. (The
Yahoo! Finance is a media property that is part of the Yahoo! network. It provides financial news,
data and commentary including stock quotes, press releases, financial reports, and original content.
It also offers some online tools for personal finance management.)
We are going to work and cover the industrial giants in the stock market and provide and collate
actual and relevant data sources from the Yahoo finance website, itself.
***Actual price data: https://finance.yahoo.com/
Stock lists:
(Index ETF: S&P 500)
• Apple: https://finance.yahoo.com/quote/AAPL?p=AAPL&.tsrc=fin-srch
• Tesla: https://finance.yahoo.com/quote/TSLA?p=TSLA&.tsrc=fin-srch
• COST: https://finance.yahoo.com/quote/COST?p=WMT&.tsrc=fin-srch
• MSFT: https://finance.yahoo.com/quote/MSFT?p=WFC&.tsrc=fin-srch
• GM: https://finance.yahoo.com/quote/GM?p=PYPL&.tsrc=fin-srch
• NVDA: https://finance.yahoo.com/quote/NVDA&.tsrc=fin-srch
****

**EDAV Final Project Assignment Footnotes**
Sample Data Set (Just for introductory purpose)
Open: The starting period of trading on a securities exchange or organized over-the-counter market
High: The high is the highest price at which a stock traded during a period.
Low: The low is the lowest price of the period.
Close: The close is a reference to the end of a trading session in the financial markets when the
markets close for the day.
Adj Close: The adjusted closing price amends a stock's closing price to reflect that stock's value
after accounting for any corporate actions.
Volume: Is the measure of how much of a given financial asset has traded in a period of time.
Resources:
https://www.docdroid.net/5gM68EW/barclays-us-equity-derivatives-strategy-impact-of-retailoptions-trading-pdf
https://www.investopedia.com/articles/investing/082614/how-stock-market-works.asp
https://www.investopedia.com/terms/i/iv.asp
