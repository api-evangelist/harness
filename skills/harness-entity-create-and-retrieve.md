---
name: harness-entity-create-and-retrieve
description: Create a new entity and then retrieve its details.
api: openapi/harness-entities-api-openapi.yml
operations:
- create-entity
- get-entity
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/harness-entities-api-openapi.yml ; every operationId checked against the contract
---

# harness-entity-create-and-retrieve

Create a new entity and then retrieve its details.

## Steps

1. 1. Use `create-entity` with required body fields for the new entity.
2. 2. Use `get-entity` with path parameters `scope`, `kind`, and `identifier` returned from the creation response.

## Rules

- Auth: include header `x-api-key` with the API key (apiKeyAuth).
- Idempotency: not required for these operations.
- Pagination: not applicable for single‑entity create/retrieve.
