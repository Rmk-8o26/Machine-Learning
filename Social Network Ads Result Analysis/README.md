# Social Network Ads — Purchase Prediction

Predict whether a user purchases a product after seeing a **social network ad**. Compares **8 classifiers**.

## Models Compared
1. Logistic Regression
2. K-Nearest Neighbors
3. Support Vector Machine (SVC)
4. Decision Tree
5. Random Forest
6. AdaBoost
7. Gradient Boosting
8. **XGBoost** (XGBClassifier, XGBRFClassifier)

## Pipeline
- EDA and feature scaling
- Train/test split
- Multi-model training with RandomizedSearchCV
- ROC curve and AUC evaluation
- Confusion matrix and classification report

## Dataset
- `Social_Network_Ads.csv` — 400 rows
- Features: Age, EstimatedSalary, Purchased (target)

## Requirements
```
pip install -r requirements.txt
```
