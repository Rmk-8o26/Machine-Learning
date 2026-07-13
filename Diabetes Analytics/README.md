# Diabetes Analytics

Predict diabetes onset using the **Pima Indians Diabetes dataset**. Compares **7 classification models** side-by-side.

## Models Compared
1. K-Nearest Neighbors (KNN)
2. Logistic Regression
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. Support Vector Machine (SVC)
7. MLP Neural Network

## Pipeline
- EDA and visualization
- Train/test split with feature scaling
- Model training and hyperparameter tuning
- Model comparison with visual outputs (`feature_importance.png`, `log_coef.png`, `knn_compare_model.png`)

## Dataset
- `diabetes2.csv` — 768 rows, 9 columns (Pregnancies, Glucose, BloodPressure, BMI, Age, Outcome, etc.)

## Requirements
```
pip install -r requirements.txt
```
