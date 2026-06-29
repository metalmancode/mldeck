# MLdeck

MLdeck is a browser-local, privacy-first AutoML product for practical CSV-based machine learning workflows. It helps users review CSV quality, explore tabular models, compare baselines, collect validation evidence, generate reports, and prepare ONNX-oriented export artifacts while keeping normal browser training and Data Quality flows local to the user's browser environment.

This is the public MLdeck documentation repository. It contains public documentation, examples, validation notes, privacy notes, security guidance, and link maps for MLdeck's public website and channels.

The private commercial MLdeck source code is not included here. This repository does not contain the private application source, training engine, workers, export internals, runtime packaging, service configuration, secrets, credentials, private prompts, admin logic, private datasets, private reports, or generated model packages.

## Public Links

- Website: https://mldeck.com/
- YouTube: https://www.youtube.com/@mldeck
- LinkedIn: https://www.linkedin.com/company/mldeck
- GitHub public documentation repo: https://github.com/metalmancode/mldeck
- Documentation index: [docs/index.md](docs/index.md)
- Public link map: [docs/public-link-map.md](docs/public-link-map.md)

Useful public pages:

- [Browser-based AutoML](https://mldeck.com/browser-based-automl)
- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)
- [Data Quality checks](https://mldeck.com/examples/data-quality-checks)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)
- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)
- [Train ML models in your browser](https://mldeck.com/train-ml-model-in-browser)

## Start Here

- [Documentation index](docs/index.md)
- [Browser-local AutoML](docs/browser-local-automl.md)
- [Data Quality](docs/data-quality.md)
- [Privacy-first architecture](docs/privacy-first-architecture.md)
- [Export artifacts](docs/export-artifacts.md)
- [Validation limits](docs/validation-limits.md)
- [Glossary](docs/glossary.md)

## Public Examples

- [Customer churn workflow](examples/customer-churn-workflow.md) and [public churn example](https://mldeck.com/examples/customer-churn-prediction)
- [CSV regression workflow](examples/csv-regression-workflow.md) and [public regression example](https://mldeck.com/examples/csv-regression-model)
- [ONNX export workflow](examples/onnx-export-workflow.md) and [public ONNX example](https://mldeck.com/examples/onnx-export-workflow)
- [Data Quality checks workflow](examples/data-quality-checks.md) and [public Data Quality page](https://mldeck.com/examples/data-quality-checks)

## Public Documentation

- [Browser-local AutoML](docs/browser-local-automl.md)
- [Data Quality](docs/data-quality.md)
- [Data Quality use cases](docs/data-quality-use-cases.md)
- [Privacy-first architecture](docs/privacy-first-architecture.md)
- [Export artifacts](docs/export-artifacts.md)
- [Validation limits](docs/validation-limits.md)
- [Browser-local vs cloud AutoML](docs/browser-local-vs-cloud-automl.md)
- [Glossary](docs/glossary.md)
- [Public link map](docs/public-link-map.md)

## Responsible Use

MLdeck results should be treated as exploratory modeling evidence until confirmed with strict validation. Important decisions require user-side review for leakage, time-dependence, class imbalance, dataset suitability, and domain-specific risks.

Exported artifacts should be tested outside MLdeck before operational use. Users should confirm schema handling, preprocessing assumptions, prediction behavior, parity with expected results, and suitability for the intended environment.

## What Not To Post Here

Do not post or upload:

- Private CSVs.
- Customer data.
- Financial, health, personal, or sensitive business data.
- Secrets, tokens, credentials, certificates, service-account files, or `.env` files.
- Generated export packages, including ONNX, PKL, wheel, ZIP, or runtime packages.
- Private MLdeck application source code, worker logic, model/export internals, proprietary prompts, or admin logic.

## Security And Privacy Notes

During normal browser training and Data Quality flows, raw CSV data stays in the browser environment. Backend services may still support account, application, consent, or control-plane features. Users remain responsible for the security of their browser, device, datasets, downloads, and exported artifacts.

See:

- [Security notes](SECURITY.md)
- [Privacy notes](PRIVACY.md)
- [Notice](NOTICE.md)
- [Contribution guide](CONTRIBUTING.md)

## Further Reading

- [Browser-local AutoML with ONNX export packages](https://www.linkedin.com/posts/reza-rasshidi_a-practical-look-at-browser-local-automl-activity-7472193205896224768-f6rC)
- [Local AutoML vs cloud AutoML](https://mldeck.com/compare/local-automl-vs-cloud-automl)
- [MLdeck vs PyCaret](https://mldeck.com/compare/mldeck-vs-pycaret)
- [MLdeck vs H2O AutoML](https://mldeck.com/compare/mldeck-vs-h2o-automl)

## License

License terms for this public documentation repository should be confirmed by the repository owner before reuse.

This repository is public documentation only, not the private MLdeck source-code repository.
