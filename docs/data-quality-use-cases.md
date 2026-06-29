# Data Quality Use Cases

MLdeck Data Quality is a browser-local CSV review workflow for checking dataset
readiness before model training. These use cases are public-safe and do not include
private screenshots, customer data, performance claims, or compliance claims.

## Check A CSV Before Model Training

Data Quality helps users inspect a CSV before starting AutoML. The review can surface
readiness signals that help decide whether the file should move forward, be cleaned, or
be discussed further.

## Review Missing Values

Missing values can affect feature usefulness, metric interpretation, and downstream
preprocessing. Reviewing missingness before training helps users understand where a
dataset may need cleanup or domain review.

## Identify Schema Clarity Issues

Unclear column names, mixed meanings, inconsistent formats, and ambiguous target
candidates can make modeling harder to interpret. Schema clarity review helps users
decide whether columns should be renamed, excluded, or investigated.

## Spot Possible Leakage-Risk Columns

Some columns may reveal the target directly or indirectly. Post-outcome status fields,
future timestamps, identifiers, duplicate indicators, and operational fields should be
reviewed before training.

## Check Target Imbalance

Target imbalance can make metrics misleading. Reviewing target distribution before
modeling helps users choose appropriate validation and interpretation approaches.

## Prepare A Discussion Report

Data Quality review can support report output for discussion with teammates, reviewers,
or domain experts. Reports should be treated as review material, not as compliance
certification or final validation evidence.

## Decide Whether A Dataset Needs Cleaning

Data Quality can help users decide whether a CSV is ready for modeling or needs
missing-value review, schema cleanup, leakage review, deduplication, or other
preparation before AutoML.

## Related Pages

- [Data Quality](data-quality.md)
- [Data Quality checks workflow](../examples/data-quality-checks.md)
- [Browser-local AutoML](browser-local-automl.md)
- [Validation limits](validation-limits.md)
- [Public Data Quality checks page](https://mldeck.com/examples/data-quality-checks)
