# House Price Prediction — Detailed Analysis

A comprehensive **3-stage ML pipeline** for the Kaggle Ames Housing dataset. Covers the full workflow from raw data to selected features.

## Notebooks

### 1. Data Analysis (`Data Analysis.ipynb`)
- Comprehensive EDA: missing values, numerical/categorical distributions, outlier detection, relationship analysis with SalePrice

### 2. Feature Engineering (`Feature_Engineering.ipynb`)
- Missing value imputation
- Temporal feature creation
- Rare label encoding for categorical variables
- MinMax scaling

### 3. Feature Selection (`Feature_Selection.ipynb`)
- Lasso Regression (L1 regularization) with `SelectFromModel`
- Automated feature elimination

## Datasets
- `train.csv` — 1,460 rows, ~81 features (Ames Housing)
- `test.csv` — 1,459 rows
- `x_train.csv` — pre-processed training data

## Requirements
```
pip install -r requirements.txt
```
