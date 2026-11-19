# Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn using Machine Learning. It uses customer information such as tenure, support tickets, monthly spending, and last login activity to identify possible churn patterns.

## Problem Statement
Customer churn can affect business growth and revenue. This project explores how machine learning can help identify customers who may be at risk of leaving a service.

## Dataset
- Total records: 12
- Total columns: 7
- Target variable: `churned`
- Features include:
  - Tenure months
  - Support tickets
  - Monthly spend (INR)
  - Last login days
  - Plan type

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Model
A Logistic Regression model was trained as a baseline classifier.

## Model Evaluation
- Accuracy: 66.67%
- Evaluation methods: Accuracy, Classification Report, Confusion Matrix

## Project Files
- `Customer_Churn_Baseline.ipynb` – Data analysis and model training notebook.
- `customer_churn_model.pkl` – Saved trained model.

## Limitations
The dataset contains only 12 records. Therefore, the model results are preliminary and cannot be considered reliable for real-world deployment. A larger and more representative dataset is required for proper evaluation.

## Responsible Use
This model is intended for educational and experimental purposes only. Predictions should not be used to make automatic decisions about customers.

## Conclusion
This project demonstrates a basic machine learning workflow for customer churn prediction, from data exploration to model evaluation.
