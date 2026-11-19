# ML Problem Framing Memo – Customer Churn Prediction

## 1. Business Problem
Customer churn occurs when customers stop using a company's service. Identifying customers who may leave can help a business plan better customer support and retention activities.

## 2. Project Objective
The objective is to build a baseline machine learning model that predicts whether a customer is likely to churn based on the available customer data.

## 3. Target Variable
- Target column: `churned`
- `0` – Customer did not churn
- `1` – Customer churned

## 4. Input Features
The model uses the following features:
- `tenure_months`
- `support_tickets`
- `monthly_spend_inr`
- `last_login_days`
- `plan_type`

The `customer_id` column is excluded because it is an identifier, not a useful predictive feature.

## 5. Machine Learning Approach
- Problem type: Binary Classification
- Algorithm: Logistic Regression
- Train-test split: 75% training and 25% testing
- Evaluation: Accuracy, Precision, Recall, F1-score and Confusion Matrix

## 6. Baseline Results
The Logistic Regression model achieved an accuracy of 66.67% on the test dataset.

These results are preliminary because the dataset contains only 12 records and the test set contains only 3 records.

## 7. Intended Use
The model is intended for educational experimentation and exploring customer churn patterns. It may help demonstrate how businesses could identify customers for supportive retention outreach.

## 8. Limitations and Risks
- Very small dataset.
- Results may not represent real customer behaviour.
- Model predictions may contain errors.
- Dataset representativeness and potential bias are unknown.
- Model performance requires testing on a larger dataset.

## 9. Responsible Decision-Making
Predictions should not be used as the sole basis for customer-related decisions. Human review and additional evidence are necessary.

## 10. Conclusion
This project demonstrates the basic process of framing a machine learning problem, preparing data, training a Logistic Regression model and evaluating its performance.
