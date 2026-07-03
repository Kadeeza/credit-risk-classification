# 💳 Credit Risk Classification — Machine Learning for Lending Decisions

![Python](https://img.shields.io/badge/Tool-Python-blue) ![scikit--learn](https://img.shields.io/badge/Tool-scikit--learn-orange) ![Pandas](https://img.shields.io/badge/Tool-Pandas-blue) ![Machine Learning](https://img.shields.io/badge/Skill-Machine%20Learning-purple) ![Financial Analysis](https://img.shields.io/badge/Domain-Finance-green)

## 📌 Project Summary

This project builds a machine learning model to classify loans as either healthy or high-risk based on borrower and loan characteristics — a core use case in the financial services industry.

Using logistic regression on historical lending data, the model learns to predict credit risk and is evaluated on its ability to correctly identify both categories, with particular attention to catching high-risk loans that could result in default.

---

## 🎯 Business Objective

Lending institutions need scalable, data-driven tools to assess creditworthiness. Manual review is time-consuming and inconsistent. A well-performing classification model can:

- Flag high-risk loans before approval
- Reduce default rates and financial losses
- Speed up credit decision workflows
- Provide an auditable, consistent decision framework

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data processing and modeling |
| scikit-learn | Logistic regression, train/test split, evaluation metrics |
| Pandas | Data preparation and feature engineering |
| imbalanced-learn | Handling class imbalance |
| Jupyter Notebook | Analysis and model development |

---

## 📊 Project Workflow

### 1. Data Preparation
- Loaded lending data from CSV
- Separated features (X) from the target variable — loan status (y)
- Split data into training and test sets

### 2. Model Training
- Fit a Logistic Regression model on the training data

### 3. Model Evaluation
- Generated predictions on the test set
- Produced a confusion matrix to visualize true/false positives and negatives
- Printed a classification report with:
  - Precision
  - Recall
  - F1-score
  - Overall accuracy

### 4. Analysis
- Assessed how well the model identifies both healthy loans (label 0) and high-risk loans (label 1)
- Summarized model performance and made a recommendation on fitness for use

---

## 💼 Business Value Delivered

This project demonstrates the ability to:

✅ Build and evaluate a binary classification model on financial data  
✅ Handle class imbalance in real-world datasets  
✅ Interpret precision, recall, and F1-score in a business context  
✅ Communicate model performance and limitations clearly  
✅ Apply machine learning to a high-stakes financial decision problem  

---

## 📁 Repository Structure

```
credit-risk-classification/
│── Credit_Risk/
│   └── credit_risk_classification.ipynb    # Model notebook
│── Resources/
│   └── lending_data.csv                    # Source dataset
│── README.md
```
