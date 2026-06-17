# MLdeck

MLdeck is a browser-local, privacy-first AutoML product for CSV-based machine learning workflows. It supports exploratory CSV upload, profiling, Data Quality review, feature and target selection, preprocessing, model comparison, baseline comparison, delta vs baseline review, validation evidence, PDF/report output, and ONNX-oriented manifest-driven export packages while keeping raw CSV data in the user’s browser during normal browser training and Data Quality flows.

Website: https://mldeck.com/

## What MLdeck is
MLdeck is designed for exploratory modeling, education, privacy-first evaluation, local CSV workflows, and export artifact testing. The product focuses on browser-local, no-code/low-code workflows for tabular CSV machine learning, with public documentation for browser-based AutoML, browser-local Data Quality review, privacy-first architecture, validation limits, and export testing.

Useful public pages:

- [MLdeck homepage](https://mldeck.com/)
- [Browser-based AutoML](https://mldeck.com/browser-based-automl)
- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)
- [Data Quality checks](https://mldeck.com/examples/data-quality-checks)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)
- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)
- [Train ML models in your browser](https://mldeck.com/train-ml-model-in-browser)

## What this repository contains
This repository contains public documentation, example workflow notes, validation guidance, security notes, privacy notes, notices, and reviewed links to MLdeck public SEO/static website pages.

## What this repository does not contain
This public repository does not contain MLdeck’s private application source code, training engine, worker implementation, export internals, custom runtime packaging, Firebase configuration, private prompts, credentials, admin logic, or proprietary implementation details.
The production application source remains private. This repository is only a public documentation, examples, and validation-notes hub.

## Public documentation
- [Browser-local AutoML](docs/browser-local-automl.md)
- [Data Quality](docs/data-quality.md)
- [Privacy-first architecture](docs/privacy-first-architecture.md)
- [Export artifacts](docs/export-artifacts.md)
- [Validation limits](docs/validation-limits.md)

## Example workflows
- [Customer churn workflow](examples/customer-churn-workflow.md) and [public churn example](https://mldeck.com/examples/customer-churn-prediction)
- [CSV regression workflow](examples/csv-regression-workflow.md) and [public regression example](https://mldeck.com/examples/csv-regression-model)
- [ONNX export workflow](examples/onnx-export-workflow.md) and [public ONNX example](https://mldeck.com/examples/onnx-export-workflow)
- [Data quality checks](examples/data-quality-checks.md) and [public Data Quality page](https://mldeck.com/examples/data-quality-checks)

## Data Quality
MLdeck Data Quality is a browser-local CSV review workflow for spotting missingness, schema clarity issues, risky columns, leakage-risk indicators, and readiness signals before training starts.

The goal is to help users decide whether a CSV is ready for AutoML, needs cleaning, or should be reviewed further before sharing or modeling. Data Quality review can produce reports and PDF-style outputs for inspection and discussion.

During normal Data Quality review, no model training starts and raw CSV data stays in the browser environment.

Related public pages:

- [Data Quality checks](https://mldeck.com/examples/data-quality-checks)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)

## Validation and responsible use
MLdeck results should be treated as exploratory evidence until confirmed with strict validation, time-aware validation where appropriate, leakage review, baseline comparison, and external artifact testing.

Related pages:

- [Local AutoML vs cloud AutoML](https://mldeck.com/compare/local-automl-vs-cloud-automl)
- [MLdeck vs PyCaret](https://mldeck.com/compare/mldeck-vs-pycaret)
- [MLdeck vs H2O AutoML](https://mldeck.com/compare/mldeck-vs-h2o-automl)

## Security and privacy notes
During normal browser training and Data Quality flows, raw CSV data stays in the browser environment. Backend services may still support account, application, consent, or control-plane features. Users remain responsible for the security of their browser, device, datasets, and exported artifacts.

See:

- [Security notes](SECURITY.md)
- [Privacy notes](PRIVACY.md)
- [Notice](NOTICE.md)

- ## Further reading

- [Browser-local AutoML with ONNX export packages](https://www.linkedin.com/posts/reza-rasshidi_a-practical-look-at-browser-local-automl-activity-7472193205896224768-f6rC)

This repository is public documentation only, not the private MLdeck source-code repository.

