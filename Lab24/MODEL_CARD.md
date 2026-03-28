# Titanic Survival Model (Logistic Regression)
**Date:** 2026-01-02T13:20:28.430497Z
**Framework:** scikit-learn 1.8.0  
**Data:** seaborn.titanic — features: pclass, sex, age, sibsp, parch, fare, embarked, class, who, alone; target: survived

## Preprocessing
- Numeric: median imputation + StandardScaler
- Categorical: most-frequent imputation + OneHotEncoder(ignore unknown)

## Metrics (hold-out 20%)
- Accuracy: 0.832
- ROC-AUC: 0.869

## Usage
