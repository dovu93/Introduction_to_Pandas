# Unit 4 Homework Assignment: A Whale Off the Port(folio)

![](https://i.redd.it/y1rh8t8udo451.jpg)

## Background

The investment division of Harold's company has been investing in algorithmic trading strategies. Some of the investment managers love them, some hate them, but they all think their way is best.

You just learned these quantitative analysis techniques with Python and Pandas, so Harold has come to you with a challenge—to help him determine which portfolio is performing the best across many areas: volatility, returns, risk, and Sharpe ratios.

You will need to create a tool (an analysis notebook) that analyzes and visualizes the major metrics of the portfolios across all of these areas, and determine which portfolio outperformed the others. You will be given the historical daily returns of several portfolios: some from the firm's algorithmic portfolios, some that represent the portfolios of famous "whale" investors like Warren Buffett, and some from the big hedge and mutual funds. You will then use this analysis to create a custom portfolio of stocks and compare its performance to that of the other portfolios, as well as the larger market (S&P 500).



### Quantitative Analysis

#### Performance Analysis:

1. From the output of block 36, we can conclude that Algorithm 1s' portfolio and Berkshire Hathaway Incs' portfolio has outperformed the S&P 500.

#### Risk Analysis:

1. Tiger Global Management LLC. has the largest spread among it's daily change. While Paulson & Co. Inc. has the smallest spread among it's daily change.

2. From the output of block 39, we can conclude that Tiger Global Management LLC. and Berkshire Hathaway Inc. have higher risk associated with them than the S&P 500 index. 

#### Rolling Statistics

1. Yes, the risk increasess for each portfolio when the risk for the S&P 500 increases. However the S&P 500 doesn't always increase when the other portfolio's risk increases.

2. Algorithm 2's portfolio closely matches the S&P 500.

3. I picked Algorithm 1. Algorithm 1's portfolio does not seem sensitive to the S&P 500.

### Plot Sharpe Ratios

2. Algorithm 1's portfolio outperformed the Whale's portfolio along with the S&P 500. Algorithm 2's portfolio fell short to the S&P 500 and Berkshire Hathaway Inc. However it did outperform all the others. 

### Create a Custom Portfolio

After creating my portfolio consisting of: AMZN, BP, NKE and DIS, I've concluded that between January 2017 and April 2019 my portfolio outperformed every portfolio except Berkshire Hathaway Inc. However looking at the sharpe ratio, we can conclude that my portfolio carries less risk for the return compared to Berkshire Hathaway Inc. 