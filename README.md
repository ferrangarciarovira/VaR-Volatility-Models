# From Volatility to Value at Risk: A Comparative Analysis Using Jump, Rough, and SABR Volatility Models

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
- SABR model

We evaluate how these affect VaR estimation based on real market data.

## Methodology

- Theoretical derivation of VaR using the Black-Scholes framework.
- Implementation of:
  - **Jump Diffusion Models (Merton and Kou)**
  - **Rough Volatility (using fractional Brownian motion)**
  - **SABR Model**
- Empirical estimation of volatility using Python.
- Sensitivity analysis and robustness checks of VaR predictions and model performance.

## Structure
```text
/data/              # Market data used for simulations
/report/            # Final thesis document and LaTeX drafts
/results/           # Visualizations and model outputs
main.py             # Script to execute full VaR analysis
README.md           # Project overview and instructions
