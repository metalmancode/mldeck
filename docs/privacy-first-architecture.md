# Privacy-First Architecture

MLdeck's public privacy posture is privacy-first and browser-local during normal training and Data Quality flows. For standard browser workflows, raw CSV data is not uploaded to MLdeck servers. This is intended to support exploratory modeling, education, local evaluation, and privacy-first CSV analysis.

Relevant public pages:

- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)
- [Datenschutz](https://mldeck.com/datenschutz.html)

## What This Means
MLdeck is designed so the user's CSV can be profiled and trained in the browser during normal browser training flows, and reviewed locally during Data Quality checks before training starts. Public documentation describes this at a product level only; this repository does not include implementation details.
Browser-side profiling and reporting help reduce unnecessary raw-data movement while preserving the user's local control over the CSV during normal browser workflows.

## Backend Services
Backend services may exist for account, consent, application, or control-plane features. The privacy claim is limited to normal browser training and Data Quality flows and raw CSV data handling in those flows.

## User Responsibility
Users remain responsible for their local device, browser profile, downloads, exported files, access controls, and dataset handling. Sensitive datasets should be reviewed according to the user's internal policies before use, and exported artifacts remain the user's responsibility once downloaded.

## No Compliance Guarantee
This repository avoids compliance guarantees. MLdeck's public privacy positioning should be read as product documentation, not legal advice or a certification.
