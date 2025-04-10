# DSSM-VAE for CMAPSS Dataset

This repository contains a Jupyter notebook implementing a **Deep State Space Model (DSSM)** combined with a **Variational Autoencoder (VAE)** to analyze and model the CMAPSS dataset for predictive maintenance.

## Dataset
The required CMAPSS data files are included in the `DATA/` folder.  
Each subset consists of three files:

- `train_FD00X.txt`
- `test_FD00X.txt`
- `RUL_FD00X.txt`

> Replace `X` with a number from `1` to `4` depending on the selected dataset (`FD001`, `FD002`, `FD003`, or `FD004`). You must use all three files from the **same subset**.

---

## Notebook

- `DSSM_VAE_cmappss_github.ipynb`:  
  Contains the full pipeline:
  - Loads CMAPSS data from `DATA/`
  - Performs preprocessing and feature engineering
  - Builds and trains a DSSM + VAE model
  - Evaluates the model on the test set
  - 
## Requirements
- Python 3.x
- TensorFlow / PyTorch (depending on your implementation)
- pandas, numpy, matplotlib, sklearn
