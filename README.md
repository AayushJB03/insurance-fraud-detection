Insurance Fraud Detection using Machine Learning
Overview

Insurance fraud is a major challenge for insurance companies, leading to significant financial losses every year. This project focuses on detecting fraudulent auto insurance claims using machine learning models.

The goal of this project is to analyze insurance claim data and build predictive models that can classify whether a claim is fraudulent or legitimate.

This project compares multiple machine learning algorithms and evaluates their performance using various classification metrics.

Dataset

This project uses the Auto Insurance Claims Dataset available on Kaggle.

Dataset link:
https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data

The dataset contains detailed information about insurance claims, including:

Customer demographics

Policy details

Incident information

Claim amount

Fraud label

Target variable:

fraud_reported

Where:

Y → Fraudulent claim

N → Legitimate claim

Project Structure
insurance-fraud-detection
│
├── data
│   └── insurance_claims.csv
│
├── notebooks
│   └── Insurance_Fraud_Detection_(Using_12_Models).ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
Machine Learning Models Used

The notebook evaluates multiple classification models:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Naive Bayes

Gradient Boosting

XGBoost

LightGBM

CatBoost

These models are trained and compared to determine which performs best for fraud detection.

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

XGBoost

LightGBM

CatBoost

Jupyter Notebook

Workflow

Data loading and exploration

Data preprocessing and cleaning

Exploratory Data Analysis (EDA)

Feature engineering

Model training

Model evaluation

Model comparison

Evaluation Metrics

Models are evaluated using standard classification metrics:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Installation

Clone the repository:

git clone https://github.com/AayushJB03/insurance-fraud-detection.git

Navigate to the project directory:

cd insurance-fraud-detection

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook
