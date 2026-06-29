# Data Quality

MLdeck Data Quality is a browser-local CSV review workflow for checking whether a
dataset is ready for browser-local AutoML. It is designed to help users inspect a CSV
before training starts, using locally visible signals rather than uploading raw rows to
a cloud review service.

## What Data Quality Checks Cover

MLdeck can surface browser-local review signals such as:

- Missingness
- Schema clarity
- Risky columns
- Leakage-risk indicators
- Readiness signals
- Report output
- PDF-style review artifacts

These checks help users decide whether a CSV should move to AutoML, be cleaned first, or
be reviewed further before sharing or modeling.

## How It Differs From AutoML

Data Quality is a review step, not a training step. It helps users understand the
structure and risks of a CSV before model fitting begins.

AutoML uses the reviewed dataset to profile, preprocess, compare models, review
baselines, and generate validation evidence and export-oriented artifacts.

## Browser-Local Behavior

During normal Data Quality review, raw CSV data stays in the browser environment. No
model training starts from the Data Quality workflow itself.

That makes Data Quality useful when the first question is not "what model should I
train?" but "is this CSV structurally ready for modeling?"

## Limitations

Data Quality does not clean data automatically. It does not train models, guarantee
model performance, or replace domain review.

Users should still validate outcomes, review any suspicious columns manually, and decide
whether the CSV is ready for training or needs more preparation.

## Related Pages

- [Documentation index](index.md)
- [Browser-local AutoML](browser-local-automl.md)
- [Data Quality use cases](data-quality-use-cases.md)
- [Glossary](glossary.md)
- [Privacy-first architecture](privacy-first-architecture.md)
- [Validation limits](validation-limits.md)
- [Data Quality checks workflow](../examples/data-quality-checks.md)
- [Data quality checks example](https://mldeck.com/examples/data-quality-checks)
