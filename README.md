# From Volatility to Value at Risk: A Comparative Analysis Using Jump, Rough, and SABR Volatility Models

This repository contains the code and documentation for my Bachelor's Thesis in Economics and Advanced Quantitative Methods at Universitat Pompeu Fabra. The project focuses on estimating the Value at Risk (VaR) of financial instruments using the Black-Scholes model, while comparing how different volatility modeling approaches affect the VaR outcome.

## Authors

- Ferran García Rovira  
- Arnau Reig Caballeria
- Miquel Muñoz García-Ramos

## Project Objective

The goal is to analyze the predictive power, robustness, and practical implications of estimating volatility using:

- Black Scholes
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
```
---

## How to Run This Project

### Prerequisites

You must have **Python 3.9+** installed.

---

### 1. Clone the repository

```bash
git clone https://github.com/ferrangarciarovira/VaR-Volatility-Models.git
cd VaR-Volatility-Models
```

### 2. Create a virtual environment and activate it
```bash
python -m venv env
env\Scripts\activate         # Windows

# source env/bin/activate   # Mac/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the notebook
```bash
pip install notebook 
jupyter notebook
```

---
