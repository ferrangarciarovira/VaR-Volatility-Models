# Value at Risk: A Comparative Analysis Using Jump and Rough Volatility Models

This repository contains the code and documentation for my Bachelor's Thesis in Economics and Advanced Quantitative Methods at Universitat Pompeu Fabra. The project focuses on estimating the Value at Risk (VaR) of financial instruments using the Black-Scholes model, while comparing how different volatility modeling approaches affect the VaR outcome.

## Authors

- Ferran García Rovira  
- Arnau Reig Caballeria
- Miquel Muñoz García-Ramos

## Project Objective

The goal is to analyze the predictive power, robustness, and practical implications of estimating volatility using:

- Standard historical volatility
- Jump Diffusion models
- Rough / Fractional volatility models

We evaluate how these affect VaR estimation and risk management decisions based on real market data.

## Methodology

- Theoretical derivation of VaR using the Black-Scholes framework.
- Implementation of:
  - **Merton's Jump Diffusion Model**
  - **Rough Volatility (e.g., using fractional Brownian motion)**
- Empirical estimation of volatility using Python.
- Backtesting of VaR predictions and comparison of model accuracy.

## Structure
```text
/data/              # Market data used for simulations
/models/            # Python code for each volatility model
/notebooks/         # Jupyter notebooks for each model or analysis step
/report/            # Final thesis document and LaTeX drafts
/results/           # Visualizations and model outputs
main.py             # Script to execute full VaR analysis
README.md           # Project overview and instructions
