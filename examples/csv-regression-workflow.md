# CSV Regression Workflow

This public-safe example describes a numeric target prediction workflow in MLdeck. It is documentation only and does not include private datasets or implementation internals.

Matching public pages:

- [CSV regression model example](https://mldeck.com/examples/csv-regression-model)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)

## Workflow
1. Upload a reviewed CSV in the browser.
2. Select a numeric target column.
3. Exclude identifiers and columns that reveal the target.
4. Review missing values, outliers, date ranges, and high-cardinality categorical columns.
5. Compare candidate models against a mean baseline.
6. Review MAE, RMSE, and R2 at a high level.
7. Validate with a strict holdout or time-aware approach when rows have temporal order.

## Interpretation
MAE can be easier to understand in target units, RMSE emphasizes larger errors, and R2 summarizes variance explained relative to a baseline. These metrics are exploratory until confirmed on properly separated validation data. Leakage and time-order mistakes can make regression results look stronger than they are.
