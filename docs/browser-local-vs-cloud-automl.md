# Browser-Local AutoML Vs Cloud AutoML

Browser-local AutoML and cloud AutoML solve different parts of the machine learning workflow. This page explains the tradeoffs neutrally and positions MLdeck within browser-local CSV workflows.

## When Browser-Local AutoML Helps

Browser-local AutoML is useful when users want lower setup friction, local CSV workflows, quick exploratory modeling, and Data Quality review before modeling. In normal MLdeck browser training and Data Quality flows, raw CSV data stays in the user's browser environment.

This approach can be a good fit for early analysis, education, dataset readiness review, privacy-first evaluation, and export artifact testing.

## When Cloud AutoML Helps

Cloud AutoML is useful when teams need scalable infrastructure, managed training resources, team-level operations, larger dataset handling, scheduled pipelines, centralized monitoring, and production integration across managed systems.

Cloud platforms may be the better fit for large-scale training, multi-user operations, production pipelines, and workflows that require managed compute beyond a local browser and device.

## MLdeck Positioning

MLdeck focuses on browser-local CSV workflows, validation evidence, reports, and export artifacts. It is designed to help users inspect data, compare exploratory models, review baselines, and prepare artifacts for external testing.

Important decisions still require strict validation and user-side verification. Users should review leakage risks, time-dependence, class imbalance, dataset suitability, exported artifact behavior, and domain constraints before relying on results.

MLdeck does not replace all cloud AutoML use cases. It provides a browser-local path for practical CSV exploration, Data Quality review, evidence gathering, and validation-oriented export testing.

## Related Pages

- [Browser-local AutoML](browser-local-automl.md)
- [Data Quality](data-quality.md)
- [Privacy-first architecture](privacy-first-architecture.md)
- [Validation limits](validation-limits.md)
- [Export artifacts](export-artifacts.md)
- [Local AutoML vs cloud AutoML](https://mldeck.com/compare/local-automl-vs-cloud-automl)
