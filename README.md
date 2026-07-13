# Machine Learning Projects

A collection of **17 machine learning and data science projects** built with Python, covering classification, regression, clustering, NLP, time series, deep learning, and hyperparameter optimization.

## Projects Overview

| # | Project | Category | Key Models / Techniques |
|---|---------|----------|------------------------|
| 1 | [Adult Salary Prediction](./Adult_salary_prediction/) | Binary Classification | Logistic Regression |
| 2 | [Cricket Asia Cup Analysis](./cricket-asia%20cup/) | Sports EDA | Plotly visualizations |
| 3 | [Customer Segmentation (Online Retail)](./Customer_Segmentation_Online_Retail/) | RFM Clustering | RFM analysis |
| 4 | [Diabetes Analytics](./Diabetes%20Analytics/) | Classification (7 models) | KNN, LR, DT, RF, GB, SVC, MLP |
| 5 | [Earthquake Prediction](./Earthquack%20Prediction%20Model/) | Regression | Linear Regression, Random Forest |
| 6 | [Granger Causality Test](./Granger%20Causality%20Test/) | Time Series / Causality | VAR, ADF/KPSS, Granger tests |
| 7 | [Heart Disease Prediction](./Heart_Disease%20Prediction/) | Binary Classification | Naive Bayes, Logistic Regression |
| 8 | [House Price Prediction](./House_Price_Prediction%20Detailed%20Analysis/) | Regression (3 notebooks) | EDA → Feature Engineering → Lasso Selection |
| 9 | [Hyperparameter Tuning](./Hyper_parameter_tuning/) | Optimization | GridSearch, RandomSearch, Optuna, Hyperopt, TPOT |
| 10 | [IMDB Sentiment Analysis](./IMDB%20Sentiment%20Analysis/) | NLP Classification | TF-IDF + Naive Bayes, SVM, Logistic Regression |
| 11 | [Income Analysis](./Income_Analysis/) | Binary Classification | Logistic Regression |
| 12 | [Laptop Price Prediction](./Laptop_Price_Prediction/) | Regression | Decision Tree, Random Forest + GridSearch |
| 13 | [Mall Customer Segmentation](./Mall%20Customer%20Segmentation/) | Clustering (4 algos) | K-Means, GMM, Agglomerative, DBSCAN |
| 14 | [Medical Cost Analysis](./Medical%20Cost%20Analysis/) | Regression | Linear Regression, Poly Features, Random Forest |
| 15 | [Placement Analysis](./Placement%20Analysis/) | Classification | Logistic Regression, XGBoost |
| 16 | [Power Consumption Forecasting](./Power%20Comsumptiion/) | Time Series / DL | LSTM (TensorFlow/Keras) |
| 17 | [Social Network Ads Analysis](./Social%20Network%20Ads%20Result%20Analysis/) | Classification (8 models) | LR, KNN, SVC, DT, RF, AdaBoost, GB, XGBoost |

## Repository Structure

```
Machine-Learning/
├── Adult_salary_prediction/           # Census income >50K prediction
├── cricket-asia cup/                  # Asia Cup cricket EDA
├── Customer_Segmentation_Online_Retail/  # RFM customer segmentation
├── Diabetes Analytics/                # Diabetes classification comparison
├── Earthquack Prediction Model/       # Earthquake magnitude regression
├── Granger Causality Test/            # Stock price causality analysis
├── Heart_Disease Prediction/          # Heart disease classification
├── House_Price_Prediction Detailed Analysis/  # Full ML pipeline (3 notebooks)
├── Hyper_parameter_tuning/            # 6 optimization techniques compared
├── IMDB Sentiment Analysis/           # Movie review sentiment NLP
├── Income_Analysis/                   # Income classification
├── Laptop_Price_Prediction/           # Laptop spec → price regression
├── Mall Customer Segmentation/        # Customer clustering
├── Medical Cost Analysis/             # Insurance cost regression
├── Placement Analysis/                # Campus placement prediction
├── Power Comsumptiion/                # LSTM time series forecasting
├── Social Network Ads Result Analysis/ # Ad purchase prediction
└── README.md
```

## Tech Stack

| Category | Libraries |
|----------|-----------|
| **Core** | Python, pandas, numpy |
| **Visualization** | matplotlib, seaborn, plotly |
| **Machine Learning** | scikit-learn, xgboost |
| **Deep Learning** | TensorFlow / Keras (LSTM) |
| **NLP** | NLTK |
| **Time Series** | statsmodels |
| **HPO** | hyperopt, optuna, scikit-optimize, TPOT |
| **Environment** | Jupyter Notebook |

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/Machine-Learning.git
   cd Machine-Learning
   ```

2. **Navigate to any project and install its dependencies:**
   ```bash
   cd "Diabetes Analytics"
   pip install -r requirements.txt
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

> **Note:** Some notebooks reference hardcoded local file paths. You may need to update dataset paths to match your local setup.
