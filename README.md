# 🚢 Titanic Survival Predictor

A machine learning project that predicts whether a Titanic passenger survived based on passenger information.

## 📌 Project Overview

The goal of this project is to build a simple classification model that predicts Titanic passenger survival using information that was available about each passenger.

The project demonstrates a complete beginner machine learning workflow:

- Data loading
- Exploratory data analysis
- Data preprocessing
- Feature selection
- Train/test splitting
- Logistic regression
- Model evaluation
- Data visualization
- Discussion of limitations

## 🧠 Model

The project uses **Logistic Regression** for binary classification.

The model uses these features:

- Passenger class
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket fare

Categorical data was converted using one-hot encoding, and missing values were handled using median imputation.

## 📊 Results

| Metric | Result |
|---|---:|
| Accuracy | 81.0% |
| Baseline Accuracy | 61.6% |
| Survivor Precision | 80% |
| Survivor Recall | 72% |
| Survivor F1-Score | 76% |

The model performed substantially better than the baseline, which demonstrates that the selected passenger features contain useful information for predicting survival.

## 🔍 Key Findings

The exploratory analysis showed substantial differences in survival rates based on passenger characteristics.

Female passengers had a considerably higher survival rate than male passengers, while passengers in higher ticket classes also had higher survival rates.

## ⚠️ Limitations

This project has several limitations:

- The Titanic dataset is relatively small and historical.
- The model uses a limited set of passenger features.
- Missing values may affect model performance.
- Logistic regression assumes a relatively simple relationship between the features and survival probability.
- Results may change with a different train/test split or model.

## 🛠️ Technologies

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## 📁 Project Files

- `titanic_ml_project.ipynb` — Complete analysis and machine learning workflow
- `requirements.txt` — Python dependencies

## 🚀 Future Improvements

Possible improvements include:

- Testing additional machine learning models
- Hyperparameter tuning
- Cross-validation
- Additional feature engineering
- Comparing multiple models
- Adding more visualizations
