# BIM_thesis_609378
## Overview
This repository contains the code and data for my thesis "Synthetic Data Augmentation for ESG Claim Classification Under Data Scarcity: A Data-Centric Experimental Study"

## Repository Structure
- `code/` — Jupyter notebooks for data generation and model experiments
- `data/` — Synthetic training data and test fold
- `results/` — CSV files with F1, precision, recall, and accuracy per condition

## How to Run
1. Open the notebooks in `code/` using Jupyter or Kaggle
2. Set your Anthropic API key to generate synthetic data
3. Run `thesis-code.ipynb` for the main experiments (RQ1&2)
4. Run `constrained-code.ipynb` for the constrained generation experiments (RQ3)

## Requirements
- Python 3.10+
- transformers, pandas, scikit-learn, anthropic

## Note
- Robustness check 3 was not conducted for the thesis in the end.
