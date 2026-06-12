# Cointegration based algorithmic trading strategies

The jupyter file [AlgoTrading](https://github.com/dsterczer/Algorithmic-Trading/blob/main/AlgoTrading.ipynb) shows how quantitive methods can amplify the profitmaking abilities of algorithmic trades. 

* It introduces a cointegration test algorithm selecting the appropriate asset pairs (asynchronous downloading is 6 times faster)
* The cointegration vector of the Johansen test helps to find a suitable hedge ratio for a linear mean reversion strategy (multiprocessed execution of the cointegration tests is 4 times faster)
* Applying Kalman Filter and Bollinger bands improve the profitability
* The momentum strategy provides a good complement to the mean reverting strategy
* Possible future development: how these strategies should be allocated to maximaze the performance of the portfolio 
