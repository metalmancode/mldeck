# Validation Limits

MLdeck provides exploratory evidence for CSV-based workflows, but exploratory metrics are not final business evidence. Model results require careful validation before they are used for important decisions.

Relevant public pages:

- [Data-quality checks example](https://mldeck.com/examples/data-quality-checks)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)

## Exploratory Evidence
Exploratory evidence can help users compare models, spot weak baselines, and identify possible data-quality issues. It is useful for early evaluation, education, and prototyping.

## Baseline Comparison
Baseline comparison helps users understand whether a model improves on simple reference behavior such as majority-class classification or mean prediction. A model that does not beat a simple baseline should be reviewed carefully.

## Strict Holdout Validation
Strict holdout validation should be used to estimate model behavior on data not used during model selection. Users should preserve a clean validation set and avoid tuning decisions that leak information from that set.

## Time-Aware Validation
When data has a time component, validation should respect temporal order. Random splits can overstate model quality if future information influences training or selection.

## Leakage Risk
Leakage can occur when features reveal the target directly or indirectly. IDs, timestamps, post-outcome status columns, duplicates, and operational fields should be reviewed before training.

## Careful Interpretation
Metrics such as accuracy, F1, MAE, RMSE, and R2 are context-dependent. Class imbalance, rare categories, changing target distributions, missingness patterns, and shifted date ranges can all change how results should be interpreted.
