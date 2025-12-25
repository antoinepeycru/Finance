Modern Portfolio Optimization with Python

Objective This project applies Modern Portfolio Theory to simulate and analyze the performance of a diversified selection of blue-chip stocks, including Visa, Procter & Gamble, Johnson & Johnson, ExxonMobil, Home Depot, NextEra Energy, and JPMorgan Chase. The goal is to identify optimal asset allocations that balance risk and return.

Project Overview This Python-based tool uses historical market data to perform 10,000 Monte Carlo simulations. It calculates expected annual returns, volatility, and Sharpe ratios to map the risk-return landscape and identify the most efficient investment strategies.

Methodology The script fetches historical daily prices via the Yahoo Finance API and calculates annualized mean returns and a covariance matrix. Each simulation assigns random long-only weights that sum to 100%. For every iteration, the model computes the expected return, portfolio volatility, and the Sharpe ratio. The optimization identifies the Maximum Sharpe Ratio portfolio for the best risk-adjusted return and the Minimum Volatility portfolio for the lowest risk exposure. A scatterplot of all simulations illustrates the tradeoff between risk and reward.

Interpretation The results highlight how diversification across sectors reduces unsystematic risk. Defensive stocks like Procter & Gamble and Johnson & Johnson stabilize the low-volatility region, while cyclical stocks like ExxonMobil provide growth drivers. The analysis provides a mathematical framework to achieve superior risk-adjusted performance compared to holding individual stocks.
