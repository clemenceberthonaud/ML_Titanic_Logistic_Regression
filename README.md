# Titanic — Logistic Regression (Kaggle)
Predicting passenger survival using Logistic Regression.  
**Kaggle public score: 79.4%**

## Approach
- Exploratory data analysis with survival distribution plots
- Feature engineering: `AllRelatives` (SibSp + Parch), `Titles` extracted from names
- Age imputation based on passenger title median
- Polynomial features (degree 2) + StandardScaler
- Hyperparameter tuning via GridSearchCV (C, penalty, solver)

## Stack
Python · pandas · scikit-learn · seaborn · matplotlib

## Results
| Set | Accuracy |
|---|---|
| Validation (local) | ~83% |
| Kaggle public leaderboard | 79.4% |

[![Open in nbviewer](https://img.shields.io/badge/Jupyter-nbviewer-orange)](https://nbviewer.org/github/clemenceberthonaud/ML_Titanic_Logistic_Regression/blob/main/ml-titanic-competition.ipynb)
