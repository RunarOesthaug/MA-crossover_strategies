# Moving Average crossover strategy

Author: Runar Oesthaug
Date: 16/02/2020

This repository contains the notebook for exploring the 100 day simple moving average, the 100 day exponential moving average, as well as the moving average convergence divergence on a variety of assets and time frames.

First import apple stock data and plot two strategies for each of the three moving averages. Afterwards we generalize the code and run a variety of backtests displaying summary statistics for each strategy.

edit 07/03/2020:
the edhec_risk_kit is a module with functions used to calculate a summary table of various measures such as annualized return, VaR, CVaR, etc. I haven't included it here because I didn't write it myself.
