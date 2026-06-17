# ONNX Export Workflow

This public-safe example describes ONNX export at a high level. It does not include conversion internals, package internals, private runtime details, or generated artifacts.

Matching public pages:

- [ONNX export workflow example](https://mldeck.com/examples/onnx-export-workflow)
- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)

## Workflow
1. Train and review an exploratory model in MLdeck.
2. Review the feature schema and target configuration.
3. Export an ONNX-oriented artifact package generated directly in the browser when available.
4. Review included metadata and manifest-style information.
5. Run parity validation outside MLdeck before relying on the exported artifact.
6. Test inference behavior with representative inputs and edge cases.

## Validation
ONNX artifacts are designed for portable ONNX Runtime inference, subject to parity validation. External testing should verify feature order, missing-value handling, categorical handling, numeric ranges, output shape, and prediction behavior.
