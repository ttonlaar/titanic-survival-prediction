# Titanic Survival Prediction

## Project Overview
This project uses machine learning to predict whether passengers aboard the Titanic survived, using passenger information such as age, sex, and passenger class.

## Goals
- Explore and prepare passenger data.
- Engineer features to improve model performance.
- Train and compare classification models.
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

## Models
- Logistic Regression
- Random Forest Classifier

## Results
Using a stratified 80/20 training-validation split with `random_state=42`:

| Metric | Logistic Regression |
|---|---:|
| Accuracy | 80.45% |
| ROC-AUC | 0.852 |

These results are from the local validation set, not the Kaggle leaderboard.

## Features
- Passenger class (`Pclass`)
- Sex
- Age
- Family size (`FamilySize`)
- Whether the passenger traveled alone (`IsAlone`)

## Tools
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Dataset
The dataset comes from the [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic/data).

## Future Improvements
- Tune model hyperparameters using cross-validation.
- Compare additional classification algorithms.
- Investigate further feature engineering.
