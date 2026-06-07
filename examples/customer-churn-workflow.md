# Customer Churn Workflow

This public-safe example outlines a typical customer churn modeling workflow in MLdeck. It is documentation only and does not include private datasets or source code.

Matching public pages:

- [Customer churn prediction from CSV](https://mldeck.com/examples/customer-churn-prediction)
- [Data-quality checks example](https://mldeck.com/examples/data-quality-checks)

## Workflow
1. Upload a reviewed CSV in the browser.
2. Select `churned` as the target when it represents the outcome to predict.
3. Exclude identifiers such as `customer_id` from model features.
4. Review possible leakage columns, such as post-cancellation status, support resolution fields, or future billing outcomes.
5. Compare candidate models against a majority-class baseline.
6. Inspect missing values, rare categories, class imbalance, and target distribution.
7. Treat results as exploratory until validated with a strict holdout or time-aware split.

## Interpretation
Churn models can be sensitive to leakage and class imbalance. A high score can be misleading if the dataset includes fields that are only known after the churn event. Strict validation should be used before relying on results for retention campaigns, financial planning, or customer decisions.
