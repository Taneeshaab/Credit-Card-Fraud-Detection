# Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using classification techniques on highly imbalanced financial transaction data. The project performs exploratory data analysis (EDA), data preprocessing, class imbalance handling, model training, and performance evaluation to identify fraudulent transactions accurately.

## Overview

Financial fraud detection is a critical problem for banks and payment providers. This project analyzes a real-world credit card transaction dataset and builds predictive models to distinguish fraudulent transactions from legitimate ones.

The dataset contains European cardholder transactions and is highly imbalanced, with fraudulent transactions accounting for a very small fraction of the total records.

## Features

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Class Imbalance Analysis
- Fraud vs Non-Fraud Distribution Analysis
- Machine Learning Model Training
- Model Performance Evaluation
- Visualization of Transaction Patterns
- Fraud Detection Prediction Pipeline

## Tech Stack

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |

## Dataset

The project uses a publicly available credit card transaction dataset containing:

- Transaction features generated through PCA transformation
- Transaction amount information
- Fraud labels indicating legitimate or fraudulent transactions

### Target Variable

| Class | Meaning |
|---------|---------|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

The dataset is highly imbalanced, with fraud cases representing approximately **0.17%** of all transactions.

## Project Workflow

```text
Credit Card Transaction Data
              |
              v
Exploratory Data Analysis
              |
              v
Data Preprocessing
              |
              v
Class Imbalance Analysis
              |
              v
Feature Preparation
              |
              v
Model Training
              |
              v
Fraud Prediction
              |
              v
Performance Evaluation
```

## Exploratory Data Analysis

The project performs:

- Dataset inspection and summary statistics
- Missing value analysis
- Class distribution analysis
- Fraud vs non-fraud comparison
- Transaction amount analysis
- Correlation analysis and visualization

## Evaluation Metrics

The fraud detection model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Installation

### Clone Repository

```bash
git clone <repository-url>
cd Credit-Card-Fraud-Detection
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
credit_card_fraud_detection.ipynb
```

## Key Highlights

- Built an end-to-end fraud detection workflow using machine learning and financial transaction analytics.
- Analyzed highly imbalanced transaction data where fraudulent cases represent only 0.17% of total records.
- Performed extensive exploratory data analysis, preprocessing, and model evaluation for fraud prediction.
- Applied data visualization techniques to uncover transaction patterns and fraud characteristics.

## Future Enhancements

- XGBoost and LightGBM-based fraud detection
- Real-time fraud monitoring dashboard
- Deep learning-based anomaly detection
- Graph-based fraud detection using GNNs
- Streaming transaction analytics
- Explainable AI (XAI) integration

## Learning Outcomes

- Fraud Detection Systems
- Classification Models
- Imbalanced Dataset Handling
- Exploratory Data Analysis
- Machine Learning
- Financial Analytics
- Data Visualization
- Model Evaluation

## License

This project is intended for educational and learning purposes.
