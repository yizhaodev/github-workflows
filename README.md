# github-workflows

Centralized GitHub Actions workflows for automation across repositories.

## Workflows

| Workflow | Description | Setup |
|----------|-------------|-------|
| [Sync Forks](.github/workflows/sync.yml) | Syncs forked repositories with their upstream sources hourly | Create a fine-grained PAT with access to all managed forks, add as secret `SYNC_UPSTREAM_REPO_TOKEN` |
