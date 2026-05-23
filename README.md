# Telecom Customer Churn Prediction & Retention Analysis

## Project Overview
This project focuses on predicting telecom customer churn using machine learning techniques. Customer churn prediction helps businesses identify customers likely to discontinue services, enabling proactive retention strategies.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model building, performance evaluation, and model comparison.

---

## Objectives
- Analyze customer behavior and churn patterns
- Identify major factors influencing churn
- Build predictive machine learning models
- Compare multiple classification algorithms
- Support customer retention decision-making

---

## Dataset Information
Dataset: Telco Customer Churn Dataset

The dataset contains telecom customer details such as:
- demographic information
- subscription details
- billing information
- service usage
- churn labels

Key features include:
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Monthly Charges
- Total Charges
- Internet Service
- Contract Type
- Payment Method
- Tech Support
- Online Security
- Streaming Services

Target Variable:
- Churn Label

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Machine Learning Models
### Logistic Regression
Used as a baseline classification model for churn prediction.

### Random Forest Classifier
Used for improved prediction performance and feature importance analysis.

---

## Model Performance
| Model | Accuracy |
|------|---------|
| Logistic Regression | ~80% |
| Random Forest | ~79% |

---

## Visualizations Included
- Customer churn distribution
- Confusion matrix
- Feature importance analysis
- Model accuracy comparison

---

## Key Insights
- Customers with higher monthly charges are more likely to churn.
- Long-term customers show significantly lower churn rates.
- Month-to-month contract users exhibit higher churn probability.
- Billing and contract-related features strongly influence churn.
- Logistic Regression and Random Forest delivered strong predictive performance.

---

## Project Structure
```bash
Telecom-Customer-Churn-Prediction-Retention-Analysis/
│
├── customer_churn_prediction.ipynb
├── Telco_customer_churn.xlsx
├── customer_churn_model.pkl
├── requirements.txt
└── README.md
