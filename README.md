# Almgren-Chriss Optimal Execution Model

The aim of the Almgren-Chriss optimal execution model is to minimize a combination of volatility risk and transaction costs arising from permanent and temporary market impact. In this notebook, we study the model for liquidation of large positions with real financial data.

## Correlated Assets
We numerically illustrate the model with financial data for two (correlated) assets. In particular, we use the daily historical prices of Alphabet Inc. (NASDAQ:GOOG) and Meta Platforms, Inc. (NASDAQ:FB) over three months.
![alt text](http://url/to/img.png)

## Cross-Market Manipulation
We explore a particular case of trading shares of the same company on different exchanges. In particular, we explore the optimal strategy for closing a position of Carnival Corporation & plc (CCL) over 15 days. CCL is a British-American cruise operator which is currently the world's largest travel leisure company. Shares of CCL are traded on both the NYSE and the LSE. See Jupyter notebook for more details.

![alt text](http://url/to/img.png)
## Reference
- (Almgren, R. and Chriss, N., 2001. Optimal execution of portfolio transactions. The Journal of Risk, 3(2), pp.5-39)[https://www.smallake.kr/wp-content/uploads/2016/03/optliq.pdf]
