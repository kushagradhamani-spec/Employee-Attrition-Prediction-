📓 Notebooks

This folder contains all the Jupyter Notebooks used for the Employee Attrition Analysis project.

📁 Structure
notebooks/
├── eda.ipynb        # Exploratory Data Analysis
└── model.ipynb      # Machine Learning Models

📌 Notebook Descriptions
🔹 eda.ipynb

Loads the raw dataset from data/raw/employee_attrition.csv.

Performs Exploratory Data Analysis (EDA):

Distribution of Attrition (Yes/No)

Attrition by Age, Department, Salary, Years at Company

Correlation heatmap

Identifies key patterns and insights.

🔹 model.ipynb

Prepares the data (encoding categorical variables, scaling if required).

Splits dataset into training and testing sets.

Applies classification algorithms:

Logistic Regression

Random Forest

Evaluates models using:

Accuracy

Recall

ROC-AUC

Provides feature importance to identify key drivers of attrition.

🚀 Usage

Run eda.ipynb first to explore the dataset.

Then run model.ipynb to train and evaluate prediction models.
