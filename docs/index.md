# MLdeck Public Documentation

This index organizes MLdeck's public documentation for GitHub visitors,
search engines, and people evaluating browser-local CSV AutoML workflows.

## What MLdeck Is

MLdeck is a browser-local, privacy-first AutoML product for practical
CSV-based machine learning workflows. It focuses on local CSV review,
exploratory modeling, baseline comparison, validation evidence, report output,
and export artifacts for external testing.

## Core Public Topics

- [Browser-local AutoML](browser-local-automl.md)
- [Data Quality](data-quality.md)
- [Data Quality use cases](data-quality-use-cases.md)
- [Privacy-first architecture](privacy-first-architecture.md)
- [Export artifacts](export-artifacts.md)
- [Validation limits](validation-limits.md)
- [Browser-local vs cloud AutoML](browser-local-vs-cloud-automl.md)
- [Glossary](glossary.md)
- [Public link map](public-link-map.md)

## Browser-Local AutoML

Browser-local AutoML helps users start CSV-based exploratory modeling without
first setting up a local Python environment or cloud notebook. MLdeck's public
workflow covers CSV upload, profiling, feature and target selection,
preprocessing choices, model comparison, baseline review, validation evidence,
and export-oriented artifacts.

Related public pages:

- [Browser-based AutoML](https://mldeck.com/browser-based-automl)
- [Train ML models in your browser](https://mldeck.com/train-ml-model-in-browser)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)

## Data Quality

Data Quality is a browser-local CSV review workflow for checking missingness,
schema clarity, possible leakage-risk columns, target imbalance, and dataset
readiness before training starts.

Related pages:

- [Data Quality documentation](data-quality.md)
- [Data Quality use cases](data-quality-use-cases.md)
- [Data Quality checks example](../examples/data-quality-checks.md)
- [Public Data Quality checks page](https://mldeck.com/examples/data-quality-checks)

## Privacy-First CSV Workflows

During normal browser training and Data Quality flows, raw CSV data stays in
the browser environment. Backend services may still support account,
application, consent, or control-plane features.

Related pages:

- [Privacy-first architecture](privacy-first-architecture.md)
- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)

## Export Artifacts And ONNX-Oriented Packages

MLdeck describes export artifacts as validation-dependent outputs for testing
outside the browser workflow. Public descriptions stay high level and do not
include export internals or generated packages.

Related pages:

- [Export artifacts](export-artifacts.md)
- [ONNX export workflow](../examples/onnx-export-workflow.md)
- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)

## Validation Boundaries

MLdeck results are exploratory evidence until confirmed with strict
validation, leakage review, time-aware validation where appropriate, and
external artifact testing.

Related pages:

- [Validation limits](validation-limits.md)
- [Customer churn workflow](../examples/customer-churn-workflow.md)
- [CSV regression workflow](../examples/csv-regression-workflow.md)

## Example Workflows

- [Customer churn workflow](../examples/customer-churn-workflow.md)
- [CSV regression workflow](../examples/csv-regression-workflow.md)
- [Data Quality checks workflow](../examples/data-quality-checks.md)
- [ONNX export workflow](../examples/onnx-export-workflow.md)

## Public Channels

- Website: https://mldeck.com/
- YouTube: https://www.youtube.com/@mldeck
- LinkedIn: https://www.linkedin.com/company/mldeck
- GitHub public documentation repo: https://github.com/metalmancode/mldeck

See the [public link map](public-link-map.md) for how these channels connect.

## Safety And Disclosure Boundaries

This repository is public documentation only. Do not post private CSVs,
customer data, sensitive examples, secrets, tokens, service-account files,
generated export packages, private reports, or private MLdeck source code.

See the [contribution guide](../CONTRIBUTING.md),
[security notes](../SECURITY.md), and [privacy notes](../PRIVACY.md) before
opening public issues or pull requests.
