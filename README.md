# CAPM-Analysis

# Business Objective

Portfolio optimization is the process of choosing the optimal portfolio (asset distribution) from a set of all possible portfolios based on some criterion. Typically, the goal is to optimize parameters like expected return while minimizing variables like financial risk. In financial sense of word, the standard deviation of a time series is referred to as Risk or volatility and the difference between two points in a time series is defined as Return.  

Optimizing the weights of asset classes to hold and optimizing the weights of assets within the same asset class are two common steps of portfolio optimization. The portfolios we create can be tailored to the preference of any individual. The said preferences are dependent on each person’s unique utility function of the form –

F (U) = αReturns – βRisk

We can see that the optimal amount of Risk and Return is proportional to the ratio of α/.

In this project, we will be creating a portfolio from stocks in the Canadian stock market. Log-returns of adjusted closing values of stocks being traded will be extracted using the Yahoo Finance API.  We will select the top-performing Stocks next. Here TSX, that is Canada Stock Market Index, is used as a benchmark. We will develop multiple portfolios, learn their investment growth rate compared to TSX and then choose the optimal portfolio by referring to the CAPM analysis on multiple portfolios and the keymatrix.

# Data Description

I will be extracting the list of companies that currently have their stocks up for trading from Wikipedia and log returns of stocks using Yahoo Finance API.
