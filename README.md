# msft-beta-spy
Beta calculation using linear regression of daily returns

📊 Beta Calculation of Microsoft (MSFT) Relative to S&P 500 (SPY)

This project calculates and visualizes the beta of Microsoft Corporation (MSFT) relative to the S&P 500 ETF (SPY) using linear regression of daily returns.

It demonstrates how to quantify systematic risk and visualize the relationship between an individual stock and the overall market.

🧠 What Is Beta?

Beta measures a stock’s sensitivity to market movements:

𝑅
𝑀
𝑆
𝐹
𝑇
=
𝛼
+
𝛽
𝑅
𝑆
𝑃
𝑌
+
𝜀
R
MSFT
	​

=α+βR
SPY
	​

+ε

β (Beta): The slope of the regression line.

β > 1 → Stock is more volatile than the market.

β < 1 → Stock is less volatile than the market.

α (Alpha): The intercept; average return not explained by the market.

R² (R-squared): Indicates how well SPY returns explain MSFT returns.

⚙️ Features

Downloads historical price data using yfinance.

Computes daily percentage returns.

Runs a linear regression using scikit-learn.

Displays beta, alpha, and R-squared values.

Plots a scatter diagram with regression line.
