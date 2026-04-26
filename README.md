# Customer-Constrained Mortgage Rate Optimization

This repository contains code for the paper:

"A Customer-Constrained Mortgage Rate Optimization Framework for Retail Banking"

## Overview

This project proposes a framework to recommend mortgage rates that:

- Maximize expected profit
- Constrain pricing to remain customer-friendly

## Dataset

This project uses a publicly available Freddie Mac dataset (preprocessed version):

https://www.kaggle.com/datasets/nikunjhemani/freddie-macs-dataset-pre-processed/data

Due to size and licensing considerations, the dataset is not included in this repository.


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

## Reproducibility

Run the notebook step-by-step to reproduce results.

## Author

Srikanth Potukuchi
