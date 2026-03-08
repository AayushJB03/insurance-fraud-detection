# Insurance Fraud Detection using Machine Learning

## Overview

Insurance fraud is a major challenge for insurance companies, leading to significant financial losses every year. This project focuses on detecting fraudulent auto insurance claims using machine learning models. The goal is to analyze insurance claim data and build predictive models that can classify whether a claim is fraudulent or legitimate.

This project compares multiple machine learning algorithms and evaluates their performance using various classification metrics to identify the best-performing model for fraud detection.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Machine Learning Models](#machine-learning-models)
- [Technologies Used](#technologies-used)
- [Workflow](#workflow)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)
- [Usage](#usage)

## Dataset

This project uses the **Auto Insurance Claims Dataset** available on Kaggle.

**Dataset link:** [https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data](https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data)

### Dataset Contents

The dataset contains detailed information about insurance claims, including:

- Customer demographics
- Policy details
- Incident information
- Claim amount
- Fraud label

### Target Variable

- **fraud_reported**: 
  - `Y` → Fraudulent claim
  - `N` → Legitimate claim

## Project Structure

```
insurance-fraud-detection/
│
├── data/
│   └── insurance_claims.csv
│
├── notebooks/
│   └── Insurance_Fraud_Detection_(Using_12_Models).ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Machine Learning Models

The notebook evaluates the following classification models:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Naive Bayes
7. Gradient Boosting
8. XGBoost
9. LightGBM
10. CatBoost

These models are trained and compared to determine which performs best for fraud detection.

## Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning library
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **XGBoost** - Gradient boosting framework
- **LightGBM** - Fast gradient boosting
- **CatBoost** - Categorical boosting
- **Jupyter Notebook** - Interactive computing environment

## Workflow

The project follows this workflow:

1. **Data Loading and Exploration** - Load and explore the dataset
2. **Data Preprocessing and Cleaning** - Handle missing values, outliers, and data quality issues
3. **Exploratory Data Analysis (EDA)** - Analyze patterns and relationships in the data
4. **Feature Engineering** - Create new features and select relevant ones
5. **Model Training** - Train multiple machine learning models
6. **Model Evaluation** - Evaluate model performance using various metrics
7. **Model Comparison** - Compare models and identify the best performer

## Evaluation Metrics

Models are evaluated using standard classification metrics:

- **Accuracy** - Overall correctness of predictions
- **Precision** - Correct positive predictions out of all positive predictions
- **Recall** - Correct positive predictions out of all actual positives
- **F1 Score** - Harmonic mean of precision and recall
- **Confusion Matrix** - Breakdown of true/false positives and negatives

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/AayushJB03/insurance-fraud-detection.git
```

2. Navigate to the project directory:

```bash
cd insurance-fraud-detection
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Download the dataset from Kaggle and place it in the `data/` directory as `insurance_claims.csv`

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open and run the `Insurance_Fraud_Detection_(Using_12_Models).ipynb` notebook in the `notebooks/` directory

4. Follow the notebook cells to execute the analysis and model training