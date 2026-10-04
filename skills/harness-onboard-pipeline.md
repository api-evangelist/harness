---
name: harness-onboard-pipeline
description: Onboard a pipeline to Harness Chaos by uploading a kubeconfig, executing onboarding, and registering the pipeline.
api: openapi/harness-onboarding-api-openapi.yml
operations:
- uploadKubeConfig
- executeOnboarding
- pipelineOnboardChaos
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/harness-onboarding-api-openapi.yml ; every operationId checked against the contract
---

# harness-onboard-pipeline

Onboard a pipeline to Harness Chaos by uploading a kubeconfig, executing onboarding, and registering the pipeline.

## Steps

1. 1. Use `uploadKubeConfig` with header `x-api-key` and body field `kubeconfigFile` to upload the kubeconfig.
2. 2. Use `executeOnboarding` with header `x-api-key` and body fields `accountId`, `orgId`, `projectId`, `pipelineId` to provision secrets, connectors, and the Kubernetes service.
3. 3. Use `pipelineOnboardChaos` with header `x-api-key` and body fields `pipelineId`, `onboardingId` to onboard the pipeline to chaos.

## Rules

- Auth: Include the API key in the `x-api-key` header (apiKeyAuth).
- Idempotency: `executeOnboarding` and `pipelineOnboardChaos` are POST operations; repeat calls may create duplicate resources.
- Errors: The API returns standard HTTP error codes; on rate‑limit exhaustion no specific limit is defined.
