# github-workflows

Centralized GitHub Actions workflows for automation across repositories.

## Workflows

| Workflow | Description | Setup |
|----------|-------------|-------|
| [Sync Forks](.github/workflows/sync.yml) | Syncs forked repositories with their upstream sources hourly | Create a fine-grained PAT with access to all managed forks, add as secret `SYNC_UPSTREAM_REPO_TOKEN` |
| [Check RHOAI Bundle Images](.github/workflows/check-rhoai-bundle-images.yml) | Daily check that batch-gateway RELATED_IMAGE_* entries exist in ODH/RHOAI bundle-patch.yaml and images are pullable | None (enable GitHub Actions notifications in [personal settings](https://github.com/settings/notifications) for failure alerts) |
