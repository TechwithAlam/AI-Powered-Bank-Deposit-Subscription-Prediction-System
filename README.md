# AI-Powered Bank Deposit Subscription Prediction System

## Project Overview

The AI-Powered Bank Deposit Subscription Prediction System is a Machine Learning project designed to help banks identify customers who are likely to subscribe to a term deposit product.

The system analyzes customer demographic, financial, and campaign-related information and predicts whether a customer will subscribe to a bank deposit scheme. This helps banks improve marketing efficiency, reduce operational costs, and increase conversion rates.

---

## Business Problem

Banks conduct marketing campaigns to promote term deposit products. Contacting every customer is costly and inefficient.

This project predicts potential customers who are more likely to subscribe, allowing banks to focus their marketing efforts on high-probability customers.

---

## Objectives

- Predict customer subscription behavior
- Improve marketing campaign effectiveness
- Reduce customer acquisition costs
- Support data-driven banking decisions
- Demonstrate Machine Learning applications in Banking Analytics

---

## Dataset

Dataset contains customer information such as:

- Age
- Job
- Marital Status
- Education
- Balance
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Information
- Previous Marketing Outcome

Target Variable:

```text
Deposit Subscription (Yes / No)
````

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Machine Learning Algorithms

* Logistic Regression
* Random Forest Classifier

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Workflow

```text
Customer Data
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Encoding
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Customer Prediction
      ↓
Business Recommendation
```

---

## Data Preprocessing

* Missing Value Handling
* Label Encoding
* Feature Selection
* Train-Test Split
* Standard Scaling

---

## Model Training

### Logistic Regression

Used as baseline classification model.

### Random Forest Classifier

Used for final prediction because of higher performance and robustness.

---

## Model Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Results

### Random Forest Performance

* Accuracy: 83.52%
* ROC-AUC Score: 0.91

### Classification Report

```text
Precision: 84%
Recall: 84%
F1-Score: 84%
```

The model demonstrates strong predictive performance and can effectively identify customers likely to subscribe to bank deposit products.

---

## Sample Prediction

```text
Customer Analysis Report

Prediction:
SUBSCRIBE

Confidence Score:
87.42%

Customer Segment:
High Potential Customer

Recommended Action:
Priority Marketing Contact
```

---

## Business Benefits

* Improved customer targeting
* Higher campaign conversion rates
* Reduced marketing expenses
* Better customer segmentation
* Enhanced banking decision-making

---

## Future Enhancements

* Flask Web Application
* Power BI Dashboard
* Customer Segmentation Module
* Explainable AI (SHAP)
* Real-Time Prediction API
* Cloud Deployment

---

## Project Structure

```text
Bank_Deposit_Prediction/
│
├── data/
│   └── bank.csv
│
├── notebook/
│   └── Bank_Deposit_Prediction.ipynb
│
├── models/
│   └── random_forest_model.pkl
│       scaler.pkl
│       model.pkl
│       bank_deposit_model.pkl
│
├── README.md
│
└── requirements.txt
```

---

## Author

Md Kamreaj Alam

B.Tech Computer Science (Artificial Intelligence)

Jamia Hamdard University

Interested in:

* Artificial Intelligence
* Machine Learning
* Data Science
* Banking Analytics

```

This README is strong enough for GitHub, internships, and ICICI Bank interview discussions.
```
