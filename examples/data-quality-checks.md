# Data Quality Checks

This public-safe example shows the intended Data Quality workflow in MLdeck. It stays high level and avoids private implementation details, screenshots, or scoring formulas.

## Typical Workflow

1. Open Data Quality in the browser.
2. Choose a CSV file for review.
3. Review the readiness snapshot.
4. Inspect missingness, schema clarity, and risky column indicators.
5. Look for leakage-risk warnings and other review signals.
6. Read or export the report or PDF-style output.
7. Decide whether to clean the data, share it, move to AutoML, or pause for deeper review.

## What This Workflow Is For

Data Quality is a browser-local review step for understanding whether a CSV is ready for modeling.

It is useful when the next decision is about dataset readiness, not model selection.

## What It Is Not

This workflow does not train models, clean data automatically, guarantee model performance, or replace human review.

Raw CSV data stays in the browser during normal Data Quality review.

## Related Pages

- [Data Quality documentation](../docs/data-quality.md)
- [Browser-local AutoML](../docs/browser-local-automl.md)
- [Privacy-first architecture](../docs/privacy-first-architecture.md)
- [Public Data Quality checks page](https://mldeck.com/examples/data-quality-checks)
