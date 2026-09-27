# Titanic Survival Prediction

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning and Deep Learning models.

The project uses the Titanic dataset and compares multiple models based on standard evaluation metrics.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Matplotlib
- Seaborn
- Streamlit
- Joblib

## Dataset

The project uses the `Titanic-Dataset.csv` dataset.

The target variable is:

- `Survived = 0` → Did not survive
- `Survived = 1` → Survived

## Models Used

### Machine Learning

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. XGBoost

### Deep Learning

1. Artificial Neural Network (ANN)
2. 1D Convolutional Neural Network (CNN)

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

The best model was selected based on F1 Score.

## Streamlit Application

A Streamlit application was developed to predict Titanic passenger survival.

The application takes passenger information such as:

- Passenger Class
- Sex
- Age
- Siblings / Spouses
- Parents / Children
- Fare
- Port of Embarkation

It then displays the predicted survival result and survival probability.

## Project Structure

Titanic-Survival-Prediction/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── models/
│   └── titanic_best_model.pkl
│
├── images/
│   └── titanic.jpg
│
├── notebooks/
│   └── Titanic_Analysis.ipynb
│
├── app.py
├── train_model.py
├── requirements.txt
└── README.md

## How to Run

Install the required libraries:


pip install -r requirements.txt


Run the Streamlit application:


streamlit run app.py

## Project Output

The application predicts whether the passenger is likely to survive and displays the survival probability.

## Author

S.Samuel Daniel.

