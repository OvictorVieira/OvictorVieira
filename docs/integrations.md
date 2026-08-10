# Integration Catalog

- GitHub API through `lowlighter/metrics`.
- WakaTime API through the metrics action.

## Authentication and Access

The workflow reads `METRICS_TOKEN`, `WAKATIME_USERNAME`, and `WAKATIME_TOKEN` from GitHub Actions secrets.

## Contracts and Data Flows

The metrics action reads GitHub and WakaTime activity and writes SVG assets referenced by `README.md`.

## Failure Modes and Retries

API rate limits, expired secrets, upstream action changes, and large GraphQL requests can fail a run. GitHub Actions supports manual reruns after the underlying problem is corrected.

## Ownership

The repository owner maintains the workflow, credentials, README, and generated asset configuration. Upstream action behavior is owned by `lowlighter/metrics`.
