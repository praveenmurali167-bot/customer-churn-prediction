# Responsible Data Card – Customer Churn Dataset

## 1. Dataset Overview
- Dataset name: Customer Churn Training Dataset
- Number of records: 12
- Number of columns: 7
- File format: CSV
- Target variable: `churned`

## 2. Dataset Features

| Feature | Description |
|---|---|
| customer_id | Customer identifier |
| tenure_months | Number of months as a customer |
| support_tickets | Number of support tickets |
| monthly_spend_inr | Monthly spending in INR |
| last_login_days | Days since last login |
| plan_type | Customer subscription plan |
| churned | Churn status (0 or 1) |

## 3. Data Quality
- No missing values were found in the dataset.
- The dataset contains numeric and categorical features.
- Data quality checks were performed using Pandas.

## 4. Intended Purpose
The dataset is used for educational machine learning experiments to explore customer churn patterns and build a baseline classification model.

## 5. Target Variable
- `0` – Customer did not churn.
- `1` – Customer churned.

## 6. Privacy Considerations
The dataset includes a customer identifier. The identifier was excluded from model training. Avoid publishing personal or confidential customer information.

## 7. Fairness Considerations
The dataset is very small, and its representativeness across customer groups is unknown. Model predictions may not be equally reliable for all customer groups.

## 8. Known Limitations
- Only 12 records are available.
- The dataset may not represent real-world customer behaviour.
- The model has limited evaluation data.
- The baseline accuracy of 66.67% should not be treated as proof of reliable performance.

## 9. Responsible Use
- Use the model for learning and experimentation.
- Do not make automatic decisions about customers based on predictions.
- Human review is necessary before taking customer-related action.
- Test with larger and more representative datasets before considering real-world use.

## 10. Conclusion
This data card documents the dataset's structure, intended purpose, quality checks, privacy considerations, fairness concerns and limitations to support responsible machine learning development.
