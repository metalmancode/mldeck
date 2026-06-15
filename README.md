# MLdeck

MLdeck is a browser-local, privacy-first AutoML MVP / early beta for CSV-based machine learning workflows. It supports exploratory CSV upload, profiling, feature and target selection, preprocessing, model comparison, baseline comparison, data-quality warnings, export artifacts, and reports while keeping raw CSV data out of MLdeck cloud upload paths during normal browser training flows.

Website: https://mldeck.com/

## What MLdeck is
MLdeck is designed for exploratory modeling, education, privacy-sensitive prototyping, local evaluation, and export artifact testing. The product focuses on browser-local workflows for tabular CSV machine learning, with public documentation for browser-based AutoML, local CSV modeling, privacy-first architecture, and export validation.

Useful public pages:

- [MLdeck homepage](https://mldeck.com/)
- [Browser-based AutoML](https://mldeck.com/browser-based-automl)
- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)
- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)
- [Train ML models in your browser](https://mldeck.com/train-ml-model-in-browser)

## What this repository contains
This repository contains public documentation, example workflow notes, validation guidance, security notes, privacy notes, notices, and reviewed links to MLdeck public website pages.

## What this repository does not contain
This public repository does not contain MLdeck’s private application source code, training engine, worker implementation, export internals, custom runtime packaging, Firebase configuration, private prompts, credentials, admin logic, or proprietary implementation details.
The production application source remains private. This repository is only a public documentation, examples, and validation-notes hub.

## Public documentation
- [Browser-local AutoML](docs/browser-local-automl.md)
- [Privacy-first architecture](docs/privacy-first-architecture.md)
- [Export artifacts](docs/export-artifacts.md)
- [Validation limits](docs/validation-limits.md)

## Example workflows
- [Customer churn workflow](examples/customer-churn-workflow.md) and [public churn example](https://mldeck.com/examples/customer-churn-prediction)
- [CSV regression workflow](examples/csv-regression-workflow.md) and [public regression example](https://mldeck.com/examples/csv-regression-model)
- [ONNX export workflow](examples/onnx-export-workflow.md) and [public ONNX example](https://mldeck.com/examples/onnx-export-workflow)
- [Data-quality checks](https://mldeck.com/examples/data-quality-checks)

## Validation and limitations
MLdeck is not enterprise-validation-grade yet. Results should be treated as exploratory evidence until confirmed with strict validation, time-aware validation where appropriate, leakage review, baseline comparison, and external artifact testing.

Related pages:

- [Local AutoML vs cloud AutoML](https://mldeck.com/compare/local-automl-vs-cloud-automl)
- [MLdeck vs PyCaret](https://mldeck.com/compare/mldeck-vs-pycaret)
- [MLdeck vs H2O AutoML](https://mldeck.com/compare/mldeck-vs-h2o-automl)

## Project maturity
MLdeck is an MVP / early beta. It is suitable for exploratory modeling and early evaluation. Strict validation should be used before relying on results for important decisions, and exported artifacts should be tested before use outside MLdeck.

## Security and privacy notes
During normal browser training flows, raw CSV data is not uploaded to MLdeck servers. Backend services may still support account, application, or control-plane features. Users remain responsible for the security of their browser, device, datasets, and exported artifacts.

See:

- [Security notes](SECURITY.md)
- [Privacy notes](PRIVACY.md)
- [Notice](NOTICE.md)

- ## Further reading

- [Browser-local AutoML with ONNX export packages](https://www.linkedin.com/posts/reza-rasshidi_a-practical-look-at-browser-local-automl-activity-7472193205896224768-f6rC)

This repository is public documentation only, not the private MLdeck source-code repository.

