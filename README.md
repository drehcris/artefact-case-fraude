# Fraud Detection | Machine Learning

## About the Project

This project focuses on detecting potentially fraudulent financial transactions using Machine Learning techniques.

The goal is to analyze historical transaction data, develop classification models, evaluate their performance, and predict potential fraud in new transactions.

## Dataset

- **Historical data (2025):** 523,525 transactions, including labeled fraud cases.
- **January 2026:** 44,451 transactions used for prediction.

## Methodology

The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Imbalanced data analysis
- Logistic Regression and Gradient Boosting
- Temporal validation and model comparison
- Classification performance evaluation
- Fraud probability estimation and prediction

## Results

Gradient Boosting achieved the best performance.

| Metric | Result |
|---|---:|
| Precision | 61.0% |
| Recall | 64.3% |
| F1-score | 62.6% |
| PR-AUC | 70.1% |
| ROC-AUC | 98.0% |

For January 2026, the model identified **2,453 potentially fraudulent transactions**, representing 5.52% of the dataset.

*These are model predictions, not confirmed fraud cases.*

## Technologies

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Jupyter Notebook

## Repository Contents

- `Case_Fraude_Modelo.ipynb` — Data analysis and Machine Learning pipeline.
- `Apresentacao_Case_Fraude.pdf` — Project presentation.
- `transacoes_jan2026_classificadas.csv` — Fraud prediction results.

