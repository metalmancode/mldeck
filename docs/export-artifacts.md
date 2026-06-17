# Export Artifacts

MLdeck describes export artifacts as validation-dependent outputs for testing outside the browser workflow. Public artifact descriptions are intentionally high level and do not expose implementation internals.

Relevant public pages:

- [Export ONNX from the browser](https://mldeck.com/export-onnx-browser)
- [ONNX export workflow example](https://mldeck.com/examples/onnx-export-workflow)

## Artifact Types
MLdeck may present exportable artifacts such as:

- ONNX package for portable inference testing, generated directly in the browser when available.
- Docker package for environment-oriented deployment testing.
- Python package for local validation and integration review.
- PDF/report for documentation and review.
- Manifest-driven integrity metadata for traceability.

## Validation Requirement
Exported artifacts should be tested before use outside MLdeck. ONNX artifacts are designed for portable ONNX Runtime inference, subject to parity validation. Users should compare expected behavior, schema handling, preprocessing assumptions, and prediction outputs before relying on exported artifacts.

## Scope
This repository does not include export internals, conversion code, package internals, private runtime packaging, or generated export files.
