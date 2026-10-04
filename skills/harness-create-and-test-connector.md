---
name: harness-create-and-test-connector
description: Create a new Harness connector and verify its connection.
api: openapi/harness-connectors-api-openapi.yml
operations:
- createConnector
- getTestConnectionResult
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/harness-connectors-api-openapi.yml ; every operationId checked against the contract
---

# harness-create-and-test-connector

Create a new Harness connector and verify its connection.

## Steps

1. 1. Use `createConnector` with the request body fields required to define the connector (e.g., `identifier`, `type`, `spec`).
2. 2. Use `getTestConnectionResult` with path parameter `identifier` of the newly created connector and include any required headers (e.g., `x-api-key`).

## Rules

- Auth: include header `x-api-key` with the API key (apiKeyAuth).
- Idempotency: not applicable; the create operation is not idempotent.
