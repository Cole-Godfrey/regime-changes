# Regime Changes

Small notebook project exploring how strategies can adapt to non-stationary market regimes.

The main notebook uses daily ETH/USDT data to compare simple supervised learning, sliding-window and memory-style features, online learning, and policy-gradient examples for regime-changing environments.

## Contents

- `regime-changes.ipynb` - main analysis notebook
- `ETH-USDT-1d.csv` - daily ETH/USDT OHLCV data
- `coin-toss-training.png` and `nonstationary_coin.png` - generated figures from the notebook

## Setup

Create and activate a Python environment, then install the notebook dependencies:

```bash
pip install jupyter pandas numpy matplotlib scikit-learn sympy torch
```

Open the notebook:

```bash
jupyter notebook regime-changes.ipynb
```

## Notes

This repo is exploratory research code. The notebook is the source of truth for the workflow and results.
