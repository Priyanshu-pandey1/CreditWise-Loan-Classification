# CreditWise-Loan-Classification 🏦

A Machine Learning project designed to automate loan eligibility screening. This project uses a Gaussian Naive Bayes classification model to predict whether a loan application should be approved or rejected based on applicant details.

## 📊 Project Overview
Manual loan processing is time-consuming and prone to human error. This project provides a data-driven approach to assess credit risk, helping financial institutions make faster and more accurate lending decisions.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn
- **Model:** Gaussian Naive Bayes (GaussianNB)
- **Environment:** Jupyter Notebook

## 📁 Dataset
The model is trained on `loan_approval_data.csv`, which includes key features such as:
- Applicant Income
- Loan Amount
- Credit History
- Education & Employment Status
- Property Area

## 📈 Model Performance
The Naive Bayes model achieved strong results on the test dataset:
- **Accuracy:** 86%
- **Precision:** ~0.81
- **F1 Score:** ~0.75
- **Recall:** ~0.70

### Confusion Matrix
| | Predicted: No | Predicted: Yes |
|---|---|---|
| **Actual: No** | 129 | 10 |
| **Actual: Yes** | 18 | 43 |
