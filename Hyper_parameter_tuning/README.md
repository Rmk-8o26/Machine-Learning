# Hyperparameter Tuning

Demonstrates **6 hyperparameter optimization techniques** on a Random Forest classifier using the Pima Indians Diabetes dataset.

## Techniques Compared
1. **GridSearchCV** — Exhaustive search over a parameter grid
2. **RandomizedSearchCV** — Random sampling from parameter distributions
3. **Bayesian Optimization** (Hyperopt) — Tree-structured Parzen Estimator
4. **Scikit-Optimize** (skopt) — Sequential model-based optimization
5. **Optuna** — Define-by-run optimization
6. **TPOT** — Genetic programming for pipeline optimization

## Dataset
- `diabetes.csv` — 768 rows, 9 columns

## Requirements
```
pip install -r requirements.txt
```
