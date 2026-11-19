# Risk Register – Customer Churn Prediction

| Risk | Potential Impact | Mitigation |
|---|---|---|
| Small dataset | Model may not generalize to new customers. | Collect more representative data and test with a larger dataset. |
| Class imbalance | Predictions may favour the more frequent class. | Monitor class-wise precision, recall and F1-score. |
| Incorrect predictions | Customers may be incorrectly identified as likely to churn or not churn. | Use human review and evaluate model errors. |
| Unknown data representativeness | Model performance may vary across customer groups. | Assess data coverage and fairness when more data becomes available. |
| Privacy concerns | Customer information may be exposed or misused. | Exclude unnecessary identifiers and protect confidential data. |
| Data drift | Customer behaviour may change over time, reducing model performance. | Monitor data and re-evaluate the model periodically. |
| Over-reliance on predictions | Businesses may make unsuitable decisions based only on model output. | Use predictions only as supporting information, not as automatic decisions. |

## Overall Risk Assessment

The current model is an educational baseline trained on only 12 records. Its reported accuracy is 66.67% on a test set of 3 records. This is not enough evidence to establish reliable real-world performance.

## Responsible AI Recommendation

Before any real-world use, collect a larger and more representative dataset, conduct proper validation, assess fairness and privacy, and ensure human oversight.

## Conclusion

Identifying risks and applying suitable safeguards are important for developing responsible and trustworthy machine learning systems.
