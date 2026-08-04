# Harness (harness)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Harness is an AI-powered software delivery platform that automates and accelerates the entire software development lifecycle from code to production. The platform provides intelligent automation across DevOps, testing and resilience, security and compliance, and cost optimization.

**URL:** [https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - DevOps, GitOps, Internal Developer Portal, Lifecycle, Software Delivery

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-04-18

## APIs

### Harness Platform API
Core platform resources including projects, organizations, connectors, secrets, users, and pipelines.

### Harness Continuous Integration API
Build, test, and artifact management with AI-powered Test Intelligence.

### Harness Continuous Delivery and GitOps API
Automated deployment with multi-cloud support and GitOps.

### Harness Feature Management and Experimentation API
Feature flags, targets, and A/B testing.

### Harness Cloud Cost Management API
FinOps with cost recommendations and AutoStopping.

### Harness Chaos Engineering API
Chaos experiments and resilience testing.

### Harness Security Testing Orchestration API
Automated security scanning with 40+ scanner integrations.

### Harness Internal Developer Portal API
Backstage-powered developer portal for software catalog.

### Harness Code Repository API
Source control management with pipeline integration.

### Harness Service Reliability Management API
SLO management and service monitoring.

### Harness Infrastructure as Code Management API
Terraform and IaC tool integration.

### Harness Supply Chain Security API
SBOM generation and artifact verification.

### Harness Software Engineering Insights API
Engineering metrics and analytics.

## Features

| Name | Description |
|------|-------------|
| AI-Powered Automation | Intelligent automation for test intelligence and deployment verification. |
| Pipeline Orchestration | Visual pipeline builder with conditional logic and approval gates. |
| GitOps Deployments | Declarative deployments with Argo CD integration. |
| Feature Flag Management | Progressive feature rollouts with A/B testing. |
| Cloud Cost Optimization | FinOps with AutoStopping and commitment orchestration. |
| Chaos Engineering | Resilience testing with chaos experiments. |
| Security Testing Orchestration | Automated scanning with 40+ scanner integrations. |
| Internal Developer Portal | Backstage-powered developer self-service. |

## Use Cases

| Name | Description |
|------|-------------|
| CI/CD Pipeline Automation | Automate build, test, and deploy workflows. |
| Progressive Feature Delivery | Roll out features with feature flags and canary deployments. |
| Cloud Cost Management | Optimize cloud spend with automated recommendations. |
| Security Compliance | Enforce policies with automated scanning. |
| Platform Engineering | Build internal developer platforms with self-service workflows. |
| SRE and Reliability | Manage SLOs and validate resilience. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub | Source code management and GitHub Actions integration. |
| Kubernetes | Native Kubernetes deployment with Helm and Kustomize. |
| AWS | Multi-service AWS integration. |
| Azure | Azure DevOps and AKS integration. |
| GCP | Google Cloud integration with GKE and Cloud Run. |
| Terraform | Infrastructure as Code management. |
| Jira | Issue tracking for deployment approvals. |
| Slack | Notifications and approval workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [harness-platform-api.yaml](openapi/harness-platform-api.yaml)

### JSON-LD

- [harness-context.jsonld](json-ld/harness-context.jsonld)

## Rules

- [harness-spectral-rules.yml](rules/harness-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
