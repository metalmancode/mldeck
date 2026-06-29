# Browser-Local AutoML

Browser-local AutoML means a CSV-based machine learning workflow can run important
exploratory steps directly in the user interface instead of requiring a local Python
setup or a cloud notebook. MLdeck presents this as a browser-local product workflow for
profiling data, selecting features and targets, applying preprocessing choices,
comparing models, reviewing baselines, and exporting validation evidence.

MLdeck uses browser technology and WebAssembly/Pyodide concepts at the product level to
reduce setup friction for CSV workflows. The goal is to make tabular modeling easier to
start while keeping normal browser training flows local to the user's browser
environment.

Relevant public pages:

- [Browser-based AutoML](https://mldeck.com/browser-based-automl)
- [Train ML models in your browser](https://mldeck.com/train-ml-model-in-browser)
- [Local AutoML for CSV files](https://mldeck.com/local-automl-csv)
- [Data Quality checks](https://mldeck.com/examples/data-quality-checks)

Related documentation:

- [Documentation index](index.md)
- [Glossary](glossary.md)
- [Browser-local vs cloud AutoML](browser-local-vs-cloud-automl.md)
- [Validation limits](validation-limits.md)

## CSV-Based Workflows

The intended public workflow is straightforward:

1. Upload a CSV in the browser.
2. Review profiling and data-quality signals.
3. Choose included and excluded features.
4. Select a target column and task type.
5. Train and compare exploratory models.
6. Review baseline comparison, warnings, delta vs baseline, and reports.
7. Export artifacts for validation and external testing.

## Why Browser-Local Execution Helps

Browser-local execution can reduce setup friction because users do not need to configure
a Python environment before starting an exploratory CSV modeling session. It can also
support privacy-first local CSV workflows because normal browser training flows do not
require raw CSV cloud upload.

## Limitations

Browser-local workflows depend on the user's browser, device CPU, memory, and dataset
shape. Large files, high-cardinality columns, leakage-prone features, time-dependent
data, and imbalanced targets still require careful review. Strict validation should be
used before relying on results for important decisions, and exported artifacts should be
tested outside MLdeck before operational use.

See [Data Quality](data-quality.md) and [Export artifacts](export-artifacts.md) for
related review steps.
