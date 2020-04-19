# Cointegration_Alpha
Course project of Attali

## Review of the paper of The Cointegration Alpha
- Strategies: Cointegration based, a classic index tradcking strategy and a long-short equity market netural stragy and their combinations.
   * difference from traditional same types of stragies: based on cointegration rather than correaltion to do portfolio optimization

- Alpha, market neutrality and traditional long-short equity stragies
  1. Alpha
  Alpha is used in hedge fund industry a proxy for excess return to active management, adjusted for risk. Two keys to a good alpha: a successful stock selection and market timing.
  * Through stock selection
  "long-short" equity strategies: not necessarily market-neutral. Buy undervalued and/or selling overvalued assets.  There is no proven evidence for a long-short strategy to be market-neutral.\
  Market netural strategies:  prove there are interdepencies between several different securities. It sometimes takes the form of convergence, ensure that, over a given time horizon, the equities will rach an assumed pricing relation. Examples: convertible securities arbitrage, futures/index arbitrage, fixed income, currency and options arbitrage, merger arbitrage or corporate structure arbitrage.\
  advantages of market neutral long-short strategies: indepence of the market direction, use more information, double alpha.\
  Possible risk of Market neutral strategies: hedge error, mismatches btw investing time horizon and the timing of positions convergence.
  Possible risk of Long short strategies: double transaction costs, low volatility and low correlation with market returns in normal circumstances may disappear in extreme market events.

- Cointegration and correlation in long-short strategies
  Correlation is valid only for stationary variables, which needs prior de-trending of prices and other level financial variables and which are always found to be integrated of order one or higher. For example, log prices are integrated of order one.  Cointegration will take advantage of the trend in the non-stationary time series. Cointegration techs have been applied to examine price linkage and information transmission mechanisms. \
  Cointegration strategies studied in this paper:
  1. index tracking:\
  cointegration => replicating the index, we will prove the track error to be a white noise process.
  2. long-short equity market neutral strategy:\
  Based on thge tracking ability of cointegrated portfolios, and we will prove our portfolio prices having a long-run equilibrium relationship with an enhanced index. We use cointegration to replication two portfolios: 'plus' benchmarks and 'minus' benchmarks, then we do long and short on these two portfolios. Our alpha is the spread between plus and minus portfolios.
  3. combinations of the previous two portfolios: the enhancement of the simple index tracking and long-short market neutral strategies by combining them to accommoodate different types of investment profiles.


- Main results:
  1. Cointegration-based index tracking is accurate with a mininum number of stocks
  2. Need to pay attention to stocks selection methods in order to reduce the transaction costs which could erode the returns of the tracking portfolios.
  3. long-short strategies are highly dependent on the stock selection method used and the spread between the "plus" and "minus" benchmarks tracked. The spread is proved to have little correlation with the market returns. However, when the spread increases, the cointegration relationship begins to break down and long-short market neutral strategy becomes more volatile. So we prefer the strategies tracking narrow spreads.
  4. We can add leverage to our long-short strategies to have a similar performance to hedge funds indexes. The return will be more volatile than the index but has a significantly lower correlation with the market returns.
  5. Combine two strategies together can improve their independent characteristics.


- Data used in the article
  Dow Jones industry average index (DJIA): They have used a reconstructed DJIA, uses the components of 2001-12-31 and fixes them and use the same divisor as the one of 2001-12-31.
  q
  h
