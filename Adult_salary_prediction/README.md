# Adult Salary Prediction

Predict whether an adult's annual salary exceeds **$50K** using census demographic data (UCI Adult dataset). Binary classification with Logistic Regression.

## Pipeline
- Data loading and preprocessing
- Exploratory data analysis
- Feature scaling with `StandardScaler`
- Logistic Regression classification
- Evaluation: confusion matrix, accuracy, classification report

## Dataset
- `adult_data.csv` (~32K rows) — training
- `adult_test.csv` (~16K rows) — test
- Features: age, workclass, education, marital-status, occupation, race, sex, capital-gain, hours-per-week, native-country

## Requirements
```
pip install -r requirements.txt
```
