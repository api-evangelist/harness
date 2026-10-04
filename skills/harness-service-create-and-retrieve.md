---
name: harness-service-create-and-retrieve
description: Create a new Service and then retrieve its details.
api: openapi/harness-services-api-openapi.yml
operations:
- createServiceV2
- getServiceV2
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/harness-services-api-openapi.yml ; every operationId checked against the contract
---

# harness-service-create-and-retrieve

Create a new Service and then retrieve its details.

## Steps

1. 1. Call `createServiceV2` with the Service payload in the request body and include the `x-api-key` header for authentication.
2. 2. Call `getServiceV2` with the `serviceIdentifier` path parameter returned from the create call, again sending the `x-api-key` header.

## Rules

- Auth: Provide the API key in the `x-api-key` request header (apiKeyAuth).
- Idempotency: The `createServiceV2` operation is not idempotent; repeat calls will create duplicate Services.
- Errors: On failure the API returns standard HTTP error codes (e.g., 4xx for client errors, 5xx for server errors).
