# Customer Churn Prediction

## Overview
This project aims to predict customer churn in a subscription-based business using historical customer data such as usage behavior and demographics. The goal is to identify which customers are likely to churn (i.e., stop using the service), enabling the business to take proactive measures to retain them.

### Dataset
The dataset contains customer information, including:

- **CreditScore**: The credit score of the customer.
- **Geography**: The country of residence of the customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Tenure**: The number of years the customer has been a customer.
- **Balance**: The average account balance of the customer.
- **NumOfProducts**: The number of bank products the customer uses.

### Project Features:
- **Data Preprocessing**: Handling missing values, encoding categorical features, and scaling numerical features.
- **Feature Engineering**: Creating new features based on existing ones to improve model accuracy.
- **Modeling**: Logistic Regression, Random Forest, and Gradient Boosting were used to predict churn.
- **Model Evaluation**: Using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC for performance evaluation.


---

## Table of Contents
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Modeling Techniques](#modeling-techniques)
- [Evaluation Metrics](#evaluation-metrics)
- [How to Run the Project](#how-to-run-the-project)
- [Results](#results)
- [Contributing](#contributing)

---

## Installation
### Requirements:
- Python 3.7 or above
- Required Libraries:
  ```bash
  pip install -r requirements.txt
