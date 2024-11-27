# Diversified Sectoral Portfolio Optimization

This notebook demonstrates how to construct a diversified portfolio using historical stock data, optimize the allocation using modern portfolio theory, and visualize the results. The analysis focuses on Indian stocks and leverages tools like `yfinance` and `PyPortfolioOpt`.

---

## Features

1. **Data Collection**:
   - Fetch historical stock prices for selected Indian stocks using `yfinance`.

2. **Portfolio Optimization**:
   - Calculate expected returns using mean historical returns.
   - Compute the covariance matrix using the Ledoit-Wolf shrinkage method.
   - Optimize portfolio weights to achieve a target risk level using the Efficient Frontier.

3. **Discrete Allocation**:
   - Allocate stocks for a given portfolio value using `PyPortfolioOpt`.

4. **Visualization**:
   - Display allocation weights in a table format.
   - Generate a pie chart for visual representation of the portfolio.

---

## Prerequisites

- Python 3.7+
- Install the following libraries:
  ```bash
  pip install yfinance PyPortfolioOpt cvxpy matplotlib pandas
