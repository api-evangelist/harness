---
name: harness-process-webhook-event
description: Process a webhook event and retrieve its processing and execution details.
api: openapi/harness-webhook-triggers-api-openapi.yml
operations:
- PipelineprocessWebhookEvent
- fetchWebhookDetails
- fetchWebhookExecutionDetails
- fetchWebhookExecutionDetailsV2
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/harness-webhook-triggers-api-openapi.yml ; every operationId checked against the contract
---

# harness-process-webhook-event

Process a webhook event and retrieve its processing and execution details.

## Steps

1. 1. Call `PipelineprocessWebhookEvent` with the event payload in the request body and include the header `x-api-key` for authentication.
2. 2. Call `fetchWebhookDetails` with query parameter `eventId` (returned from step 1) and header `x-api-key`.
3. 3. Call `fetchWebhookExecutionDetails` with path parameter `eventId` (same ID) and header `x-api-key`.
4. 4. Optionally call `fetchWebhookExecutionDetailsV2` with the same `eventId` and header `x-api-key` for extended execution details.

## Rules

- Authentication: Provide the API key in the `x-api-key` header for all requests.
- Idempotency: The POST endpoints (`PipelineprocessWebhookEvent`, `processCustomWebhookEvent*`) are not guaranteed to be idempotent; callers should ensure they do not resend the same payload unintentionally.
- Pagination: Not applicable – none of the listed operations support paginated responses.
- Errors: On failure the API returns standard HTTP error codes; no specific rate‑limit headers are defined.
