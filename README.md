# Credit Card Fraud Detection Using Artificial Neural Network (ANN)

## Project Overview

Credit card fraud is one of the major challenges faced by financial institutions worldwide. Fraudulent transactions can lead to significant financial losses and security concerns.

This project develops a Deep Learning-based Credit Card Fraud Detection System using an Artificial Neural Network (ANN) to classify transactions as fraudulent or legitimate.

The model is trained on historical credit card transaction data and evaluated using multiple performance metrics including Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC Score.

---

## Business Problem

Financial institutions process millions of transactions daily. Detecting fraudulent transactions manually is difficult and time-consuming.

The objective of this project is to build a machine learning solution capable of identifying suspicious transactions automatically and helping organizations minimize financial losses.

---

## Dataset Information

Dataset Source:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Dataset Characteristics:

- Total Transactions: 284,807
- Fraud Transactions: 492
- Non-Fraud Transactions: 284,315
- Features: 31
- Target Variable: Class

Target Classes:

- 0 → Legitimate Transaction
- 1 → Fraudulent Transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

- Load Credit Card Transaction Dataset

### 2. Data Understanding

- Dataset Overview
- Data Types
- Statistical Summary

### 3. Data Preprocessing

- Missing Value Analysis
- Feature Scaling
- Data Preparation

### 4. Exploratory Data Analysis (EDA)

- Fraud vs Non-Fraud Distribution
- Correlation Heatmap
- Feature Analysis

### 5. Model Development

Artificial Neural Network Architecture:

Input Layer

↓

Dense Layer (64 Neurons)

↓

Dropout Layer (0.3)

↓

Dense Layer (32 Neurons)

↓

Dropout Layer (0.3)

↓

Output Layer (Sigmoid)

---

### 6. Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- ROC Curve

---

## Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 99.95% |
| Precision | 84% |
| Recall | 77% |
| F1 Score | 80% |
| ROC-AUC | 97.8% |

---

## Key Business Insights

- The ANN model successfully distinguishes fraudulent and legitimate transactions with a ROC-AUC score of 97.8%.
- Precision of 84% indicates that most fraud predictions are correct.
- Recall of 77% demonstrates the model's ability to identify the majority of fraudulent transactions.
- The system can help financial institutions detect suspicious activities and reduce financial losses.

---

## Project Structure

```
Credit-Card-Fraud-Detection-Using-ANN/
│
├── Credit_Card_Fraud_Detection.ipynb
├── creditcard.csv
├── credit_card_fraud_ann_model.h5
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection-Using-ANN.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Implement SMOTE for handling class imbalance.
- Hyperparameter Tuning.
- Deploy model using Streamlit.
- Real-time fraud detection pipeline.

---

## Author

Shraddha Mandavkar

B.Sc. Information Technology Graduate

Aspiring Data Analyst | Machine Learning Enthusiast

LinkedIn:
www.linkedin.com/in/shraddhamandavkar12

GitHub:
github.com/mandavkars072-sketch
