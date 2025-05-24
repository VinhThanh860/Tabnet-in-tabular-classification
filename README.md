# A Comparative Study of TabNet, XGBoost, and CatBoost for Tabular Classification on Forest CoverType

This repository contains a Jupyter Notebook (`doanpython.ipynb`) that presents a comparative study of three powerful machine learning models for tabular data classification: **TabNet**, **XGBoost**, and **CatBoost**. The models are evaluated on the Forest CoverType dataset.

## Contents

- **Data Preparation:** Loads and preprocesses the Forest CoverType dataset, including feature engineering and normalization.
- **Model Training:** Trains TabNet, XGBoost, and CatBoost classifiers using consistent data splits.
- **Evaluation:** Compares models based on accuracy, F1 score, and training time.
- **Visualization:** Plots performance metrics and TabNet feature importances.

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- pytorch-tabnet
- xgboost
- catboost
- torch

You can install the required libraries using:

```python
!pip install pytorch-tabnet xgboost catboost scikit-learn pandas numpy matplotlib seaborn torch
```

## Usage

1. Download the Forest CoverType dataset and update the path in the notebook if needed.
2. Open `doanpython.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to reproduce the experiments and visualizations.

## Results

The notebook reports and visualizes the accuracy, F1 score, and training time for each model, helping users understand the strengths and trade-offs of TabNet, XGBoost, and CatBoost on this dataset.

---

Feel free to use or adapt this notebook for your own tabular data classification tasks!