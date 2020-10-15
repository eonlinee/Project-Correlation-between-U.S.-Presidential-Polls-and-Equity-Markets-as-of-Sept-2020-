# Project-Correlation-between-U.S.-Presidential-Polls-and-Equity-Markets-as-of-Sept-2020-
Hypothesis:
Markets have been on an uptick and continue to keep momentum as we draw near to the US Presidential elections. Polls, like markets, are sentiment-based and we expect to see investor sentiments reflected in polls and vice versa. 
for this project, we wish to verify if the US Presidential polls have explanatory value for the S&amp;P stock market performance. In particular, we started off with the hypothesis that the incumbent's poll rates will be more likely to correlate with stock markets, i.e. Donald Trump's likelihood to win/lose may be more linked to stock markets.

Methodology:
In terms of the X-variable, we set this as poll results. For the Y-variable, we set this as the stock market performance. For the X-variable, we are looking specifically at the top Democrat and Republican candidate, e.g. Donald Trump and Joe Biden. In terms of data sets, we look at data from the S&P markets, as well as poll data from Kaggle which is cross-checked with live poll data from Financial Times. We chose to look at S&P due to the focus on stocks in the United States. To reduce the chances of spurious correlation, we also looked at two highly possible confounders for the correlation between . These are (1) the tendency of stock markets to show seasonal fluctuations and (2) impact of the unprecedented COVID on stock markets. 

Findings:
Contrary to expectation, we concluded that there is actually a stronger correlation between the opposition candidate, as opposed to the incumbent, with the stock market. In addition, we also controlled for the seasonality effect on stock markets through programming functions. Thereafter, we also proved that the impact of COVID on stock markets can be nullified, by showing that the incremental rate of infections normalises into a flatline over time. To control for these two factors, we focused our analysis on May 2020 to date. 
