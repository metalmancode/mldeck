# MLdeck Public Glossary

These definitions are public, non-proprietary explanations for MLdeck documentation. They are not legal, security, compliance, or performance guarantees.

## Browser-Local AutoML

An AutoML workflow where important CSV profiling, modeling, review, and reporting steps run in the user's browser environment during normal product flows.

## CSV Workflow

A tabular machine learning workflow that starts from a CSV file and moves through review, feature selection, target selection, modeling, validation, and reporting.

## Data Quality Review

A pre-modeling review step for checking dataset readiness signals such as missingness, schema clarity, risky columns, leakage-risk indicators, and target imbalance.

## Leakage Risk

The risk that a feature directly or indirectly reveals the target, future information, or post-outcome state in a way that makes validation results look stronger than they are.

## Baseline Comparison

A comparison between a candidate model and a simple reference behavior, such as majority-class prediction for classification or mean prediction for regression.

## Delta Vs Baseline

The difference between a candidate model's metric and the baseline metric, used as an early signal of whether the model adds useful predictive value.

## Validation Evidence

Review material such as metrics, warnings, baseline comparisons, data-quality notes, and reports that help users assess exploratory model behavior.

## Strict Validation

Validation that keeps evaluation data separate from model selection and tuning so results better estimate behavior on unseen data.

## Time-Aware Validation

Validation that respects temporal order when records have a time component, reducing the risk that future information influences training or selection.

## Export Artifact

A file or package produced for review or external testing, such as a report, manifest-oriented package, or ONNX-oriented package.

## ONNX-Oriented Export Package

An export package intended to support ONNX Runtime inference testing when available, subject to external parity validation and user-side verification.

## Manifest-Driven Export Package

An export package organized around metadata that describes expected inputs, outputs, artifact contents, and validation context at a high level.

## Browser Environment

The user's local browser context, including the browser tab, runtime capabilities, local device constraints, downloads, and browser-managed storage behavior.

## Control-Plane Service

A backend service that may support account, application, consent, or product-management features without being part of the normal raw CSV training path.

## Raw CSV Data

The original row-level CSV content selected by the user for review or modeling.

## User-Side Verification

The user's responsibility to review datasets, validation setup, leakage risks, exported artifacts, and external behavior before relying on results.

## Related Pages

- [Documentation index](index.md)
- [Browser-local AutoML](browser-local-automl.md)
- [Data Quality](data-quality.md)
- [Validation limits](validation-limits.md)
- [Export artifacts](export-artifacts.md)
