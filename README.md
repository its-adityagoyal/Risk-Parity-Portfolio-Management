# Risk Parity Portfolio Management

This repository implements a **Risk Parity** portfolio optimization strategy, a modern alternative to traditional capital allocation methods such as Equal Weighting and Market Capitalization Weighting. The goal is to construct a portfolio where each asset contributes equally to the overall risk.

## What is Risk Parity?

Risk Parity is an asset allocation strategy that focuses on **equalizing risk contribution** from all portfolio components rather than equally allocating capital. By doing so, it enhances portfolio diversification, improves resilience to market shocks, and reduces concentration risk.

## Repository Structure
├── README.md          # This file  
├── notebook.ipynb     # Main implementation and visualization notebook  
├── references.txt     # Research and reference materials  
├── requirements.txt   # List of dependencies  


## 📚 Key Concepts

- **Volatility & Covariance Matrix (Σ)**  
  Portfolio volatility is computed using the covariance matrix of asset returns.

- **Marginal Risk Contribution (MRC)**  
  MRC quantifies the risk an asset contributes to the portfolio.

- **Equal Risk Contribution (ERC)**  
  The goal is to find weights such that each asset’s contribution to portfolio risk is equal.

- **Optimization Using SQP (Sequential Quadratic Programming)**  
  The optimization problem is solved numerically using `scipy.optimize.minimize()` with the SLSQP method.

## 🔍 Notebook Highlights

- Fetching data using **`yfinance`**
- Computing **covariance matrix**
- Implementing **portfolio volatility** and **MRC**
- Solving the optimization problem using **SLSQP**
- Evaluating **portfolio performance using optimized weights**

## Requirements

Install the required dependencies using:

```bash
pip install -r requirements.txt
```


