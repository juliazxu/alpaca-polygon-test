Testing Alpaca and Polygon API/SDK for trading algos

Links for easy access:

Alpaca paper trade account
https://app.alpaca.markets/paper/dashboard/overview

Alpaca py SDK
https://alpaca.markets/sdks/python/

Old day trading tutorial
https://medium.com/automation-generation/build-a-day-trading-algorithm-and-run-it-in-the-cloud-for-free-805450150668

Polygon API docs
https://polygon.io/docs/stocks/get_v1_indicators_macd__stockticker

Polygon dashboard
https://polygon.io/dashboard

4 TI that Polygon offers
SMA
EMA
MACD
RSI

Process / ideas
1. Build backtesting framework
2. Build websocket connections
3. Test various combinations of criteria. For example, trading indicators such as MACD crossover - see https://www.investopedia.com/trading/macd/
4. Run in cloud

Notes
Alpaca currently does not allow shorting, I believe... but it does have options but options are a lot more complicated due to IV
Alpaca does have crypto. Generally I prefer day trades to start but swing trades (particularly for crypto) are also possible.

Ideas for criteria
Volume requirement
Momentum
Trend following
Sentiment analysis
Twitter influencers
Pairs trading convergence
net neutral basis
Calendar volatility