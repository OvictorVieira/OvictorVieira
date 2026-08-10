# System Overview

The repository is a static GitHub profile backed by automatically generated metric images.

## Technology Stack

- Markdown and SVG.
- YAML-based GitHub Actions workflow.
- `lowlighter/metrics` for metric rendering.

## Module and Service Boundaries

- `README.md` defines the visible profile.
- `.github/workflows/metrics.yml` configures metric generation.
- `metrics/` stores generated SVG output.

## Data and Request Flows

GitHub Actions authenticates to the configured providers, collects profile activity, renders SVG files, and commits updated assets. GitHub then serves those assets from the default branch to the profile README.

## Architecture Invariants

- Generated SVG files must not be edited manually.
- README image paths must match the workflow output paths.
- Secrets remain in GitHub Actions configuration and are never committed.
