# Infrastructure Overview

This repository publishes the GitHub profile for `OvictorVieira`. GitHub renders `README.md`, while GitHub Actions regenerates the SVG metric assets.

## Environments

- GitHub repository: source and profile hosting.
- GitHub Actions: scheduled and manually triggered metric generation.

## Core Services and Dependencies

- GitHub Actions.
- `lowlighter/metrics` action.
- GitHub and WakaTime APIs.

## Deployment and Operations

Merging to `main` publishes README changes immediately. The metrics workflow updates generated SVG assets on its configured schedule or through manual dispatch.

## Known Constraints and Risks

Metrics generation depends on third-party actions, APIs, rate limits, and repository secrets. Generated SVG commits can conflict with long-running branches.
