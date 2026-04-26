# Customer-Constrained Mortgage Rate Optimization

This repository contains code for the paper:

"A Customer-Constrained Mortgage Rate Optimization Framework for Retail Banking"

## Overview

This project proposes a framework to recommend mortgage rates that:

- Maximize expected profit
- Constrain pricing to remain customer-friendly

## Key Results

- Model AUC: ~0.79
- Average rate reduction: ~12.5 basis points
- Profit reduction: ~3.97%

## Notebook

The full implementation is available in:

notebook/mortgage_rate_optimization.ipynb

It includes:
- Data preprocessing
- Model training (XGBoost)
- Profit formulation
- Optimization framework
- Plot generation

## Figures

Key results include:
- Profit vs Rate curve
- Aggregate profit curve
- Rate distribution shift

## Paper

PDF available at:

paper/mortgage_optimization.pdf

## Dataset

Based on publicly available Freddie Mac loan-level data.

## Reproducibility

Run the notebook step-by-step to reproduce results.

## Author

Srikanth Potukuchi
