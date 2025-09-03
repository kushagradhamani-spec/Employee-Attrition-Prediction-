# Employee Attrition Prediction

## Project Overview
This project predicts whether an employee is likely to leave the company (attrition) based on historical employee data. The goal is to help HR departments identify at-risk employees and take proactive measures to retain talent.

---

## Project Structure

Employee-Attrition-Prediction/
├── data/
│ ├── raw/ # Original dataset
│ │ └── employee_attrition.csv
│ └── processed/ # Optional: cleaned/processed data
├── notebooks/
│ ├── eda.ipynb # Exploratory Data Analysis (optional)
│ └── model.ipynb # Model training (optional)
├── models/ # Saved trained models
│ ├── logistic_regression_model.pkl
│ ├── random_forest_model.pkl
│ ├── scaler.pkl
│ └── feature_columns.pkl
├── scripts/ # Python scripts
│ ├── train.py # Train models
│ └── predict.py # Predict attrition for new employees
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .gitignore # Git ignore file
