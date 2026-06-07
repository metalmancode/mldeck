# Privacy-First Architecture

MLdeck's public privacy posture is privacy-first and browser-local during normal training flows. For standard browser training workflows, raw CSV data is not uploaded to MLdeck servers. This is intended to support exploratory modeling, education, local evaluation, and privacy-sensitive prototyping.

Relevant public pages:

- [Privacy-first AutoML](https://mldeck.com/privacy-first-automl)
- [AutoML without uploading raw CSV data](https://mldeck.com/automl-without-uploading-data)
- [Datenschutz](https://mldeck.com/datenschutz.html)

## What This Means
MLdeck is designed so the user's CSV can be profiled and trained in the browser during normal browser training flows. Public documentation describes this at a product level only; this repository does not include implementation details.

## Backend Services
Backend services may exist for account, application, or control-plane features. The privacy claim is limited to normal browser training flows and raw CSV data handling in those flows.

## User Responsibility
Users remain responsible for their local device, browser profile, downloads, exported files, access controls, and dataset handling. Sensitive datasets should be reviewed according to the user's internal policies before use.

## No Compliance Guarantee
This repository avoids compliance guarantees. MLdeck's public privacy positioning should be read as product documentation, not legal advice or a certification.
