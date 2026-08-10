# Environment Matrix

| Environment | Purpose |
| --- | --- |
| Local checkout | Review and edit source files |
| GitHub Actions | Generate metric assets |
| GitHub profile | Serve the default-branch README and SVG files |

## Configuration and Secrets Boundaries

Workflow configuration is committed in YAML. Tokens and usernames required by external services are stored as GitHub Actions secrets.

## Deployment Differences

Local changes are not visible publicly. GitHub publishes profile content from `main`, and Actions-generated assets appear only after a successful workflow commit.

## Operational Access

Maintainers need repository write access to publish changes and Actions access to manage workflow runs and secrets.
