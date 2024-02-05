# Market-Risk

This repository is dedicated to conducting a comprehensive market risk analysis of the Natixis stock using historical data from January 2015 to December 2016. The project includes several exercises, each focusing on different aspects of market risk and price modeling.

## Exercises and Objectives

Question A: Historical VaR Estimation
Objective: Estimate a historical Value at Risk (VaR) on one-day price returns using a non-parametric distribution with an Epanechnikov Kernel.
Features: The VaR estimation is adjustable for different probability levels to accommodate varying risk appetites.

Question B: Expected Shortfall and Volatility Analysis
Objective: Calculate the expected shortfall and compare it to the VaR. Additionally, compute the volatility, upper, and lower semi-deviations for Natixis stock for each year within the dataset.
Analysis: Evaluate the riskiness of the stock for each year and draw conclusions based on the computed measures.

Question C: Extreme Value Theory (EVT) Analysis
Objective: Analyze daily returns using EVT, determine the extremal index for distribution tails, and adapt the EVT VaR to account for return dependencies.
Methodology: Implement block or run de-clustering methods for extremal index calculation.

Question D: Almgren and Chriss Model Specification
Objective: Estimate all parameters of the Almgren and Chriss model to determine its specification and derive an optimal liquidation strategy based on hourly transaction opportunities.

Question E: Multiresolution Analysis
Objective: Use Haar wavelets to determine multiresolution correlations between FX rates, investigate the Epps effect, calculate Hurst exponents, and determine annualized volatility using daily volatility and Hurst exponents.

## Data
The dataset includes the daily prices of Natixis stock between January 2015 and December 2016 and FX rates for GBPEUR, SEKEUR, and CADEUR.
