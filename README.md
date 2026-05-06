# github-workflows

Centralized GitHub Actions workflows for automation across repositories.

## Setup

Create a fine-grained Personal Access Token (PAT) with repository access to all managed forks, and add it as a repository secret named `SYNC_UPSTREAM_REPO_TOKEN`.

## Workflows

### Sync Forks

Syncs forked repositories with their upstream sources hourly.

| Fork | Upstream | Branch |
|------|----------|--------|
| yizhaodev/batch-gateway | llm-d-incubation/batch-gateway | main |
| yizhaodev/llm-d-async | llm-d-incubation/llm-d-async | main |
| yizhaodev/llm-d-inference-sim | llm-d/llm-d-inference-sim | main |
| yizhaodev/llm-d-batch-gateway-operator | opendatahub-io/llm-d-batch-gateway-operator | main |
| yizhaodev/opendatahub-operator | opendatahub-io/opendatahub-operator | main |
