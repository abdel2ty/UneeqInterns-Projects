# UneeqInterns Internship Tasks

> This repository contains two machine learning projects developed as part of the UneeqInterns internship program:

![Roadmap](./cover.png)

---

---

## 1️⃣ Task 1 – Customer Churn Prediction

### Project Overview
Customer churn is one of the most critical challenges faced by subscription-based businesses. Losing existing customers directly impacts revenue, and retaining them is often more cost-effective than acquiring new ones. This project builds ML models to predict whether a customer is likely to churn using demographic, behavioral, and transactional data.

### Objective
Develop predictive models that accurately identify potential churners. Special emphasis is placed on recall to capture high-risk customers.

### Dataset
Separate training and testing datasets with customer information including age, usage, subscription, and spending patterns. The target variable is `Churn`.

### Approach
- Exploratory Data Analysis (EDA) to understand customer behavior
- Feature engineering and preprocessing
- Training multiple models (Logistic Regression, Random Forest, Gradient Boosting)
- Model evaluation and comparison
- Feature importance and confusion matrix analysis

### Key Insights
- Payment delays, support calls, and usage patterns strongly impact churn.
- Gradient Boosting showed the best recall for potential churners.
- Confusion matrix and feature importance reveal actionable patterns for retention strategies.

---

## 2️⃣ Task 2 – Healthcare Diagnosis Prediction

### Project Overview
Accurate and timely medical diagnosis is crucial for effective healthcare management. This project predicts patient medical conditions using demographic, clinical, and hospital-related data.

### Objective
Develop and evaluate predictive models that classify patients' medical conditions, emphasizing both accuracy and interpretability to support healthcare decisions.

### Dataset
Contains patient demographics, hospital admission details, insurance, billing, medications, and test results. The target variable is `Medical Condition`.

### Approach
- Exploratory Data Analysis (EDA)
- Feature engineering (AgeGroup, Length of Stay, Billing per Day, Test Results encoding)
- Preprocessing pipeline with scaling and one-hot encoding
- Training models: Logistic Regression, Random Forest, Gradient Boosting
- Evaluation using accuracy, F1-score, confusion matrix
- Feature importance analysis

### Key Insights
- Length of Stay, AgeGroup, BillingPerDay, and Test Results are key predictors.
- Gradient Boosting captured subtle patterns better than Logistic Regression.
- Multi-class classification is challenging due to multiple medical conditions and class imbalance.
- Confusion matrix highlights misclassification patterns, guiding feature improvements.

---