# Financial Derivatives Pricing and Risk Analysis

## Project Overview

This project models and analyzes derivative instruments, specifically European call options, using real market data. It applies quantitative finance techniques to estimate volatility, price options with the Black-Scholes model, and measure portfolio risk through Value at Risk (VaR) analysis.

The goal is to bridge theory and practice, showcasing how pricing, volatility modeling, and risk metrics work together in financial decision-making.


## Objectives
* Collect and clean financial market data (AAPL)
* Model and forecast stock volatility using both historical and GARCH methods
* Price European call options using the Black-Scholes model
* Compute Greeks to understand option sensitivities
* Construct a portfolio combining stock and derivatives.
* Quantify portfolio risk using Parametric and Monte Carlo Value at Risk (VaR).


## Concepts & Techniques Used
* **Volatility Modeling**: Historical standard deviation, GARCH(1,1)
* **Option Pricing**: Black-Scholes model for European calls
* **Option Sensitivities**: Delta, Gamma, Theta, Vega, Rho
* **Risk Analysis**: Parametric and Monte Carlo Value at Risk
* **Visualization**: Stock returns, volatility trends, loss distributions



## Tools & Libraries
* Python: Pandas, NumPy, SciPy, Matplotlib, Seaborn
* Finance Libraries: yfinance (data), arch (GARCH modeling)
* Jupyter Notebook: Full analysis workflow


## Key Results
* Volatility: GARCH captures clustering better than historical volatility
* Option Pricing: Deep ITM calls behave close to underlying stock (Δ ≈ 1)
* Risk: Monte Carlo VaR offers more realistic loss distribution tails
* Portfolio Insight: Combining derivatives and stock positions refines exposure and risk

## Future Work
* Extend to implied volatility surface analysis
* Add dynamic delta-hedging and Expected Shortfall (CVaR)
* Develop interactive Streamlit dashboard for pricing and risk visualization

---