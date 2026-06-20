# Agenta (agenta)

Agenta is an open-source LLMOps platform that brings prompt management, LLM evaluation, and LLM observability together in one place. Its cloud REST API at https://cloud.agenta.ai/api exposes apps and variants, versioned prompt configurations, evaluations and evaluators, testsets, and OpenTelemetry-based tracing, all authenticated with a Bearer API key. The platform is MIT licensed and can be self-hosted or used via Agenta Cloud.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/agenta/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/agenta/refs/heads/main/apis.yml)

## Tags

- AI
- LLMOps
- Prompt Management
- LLM Evaluation
- Observability

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Agenta Apps and Variants API

Create and manage LLM applications and their variants, including revisions, forking, committing, and deploying. Variants hold versioned prompt and parameter configurations that power Agenta's prompt management workflow.

- **Human URL:** [https://docs.agenta.ai/reference/api/list-api-endpoints](https://docs.agenta.ai/reference/api/list-api-endpoints)
- **Base URL:** `https://cloud.agenta.ai/api`

#### Tags

- Apps
- Variants
- Prompt Management

#### Properties

- [Documentation](https://docs.agenta.ai/prompt-engineering/overview)
- [API Reference](https://docs.agenta.ai/reference/api/list-api-endpoints)
- [OpenAPI](openapi/agenta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agenta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agenta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Agenta Configs and Prompts API

Fetch and deploy versioned prompt configurations by application, variant, or environment so production code can pull the latest committed prompt without a redeploy. Backs Agenta's configuration management SDK.

- **Human URL:** [https://docs.agenta.ai/prompt-engineering/integrating-prompts/fetch-prompt-programatically](https://docs.agenta.ai/prompt-engineering/integrating-prompts/fetch-prompt-programatically)
- **Base URL:** `https://cloud.agenta.ai/api`

#### Tags

- Configs
- Prompts
- Versioning

#### Properties

- [Documentation](https://docs.agenta.ai/prompt-engineering/integrating-prompts/fetch-prompt-programatically)
- [API Reference](https://docs.agenta.ai/reference/sdk/configuration-management)
- [OpenAPI](openapi/agenta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agenta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agenta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Agenta Evaluations and Evaluators API

Run and manage evaluations and configure evaluators (LLM-as-a-judge, exact match, similarity, custom code, and more) to score variants against testsets, with queues, runs, results, and metrics.

- **Human URL:** [https://docs.agenta.ai/reference/api/evaluations](https://docs.agenta.ai/reference/api/evaluations)
- **Base URL:** `https://cloud.agenta.ai/api`

#### Tags

- Evaluations
- Evaluators
- LLM Evaluation

#### Properties

- [Documentation](https://docs.agenta.ai/evaluation/overview)
- [API Reference](https://docs.agenta.ai/reference/api/evaluations)
- [OpenAPI](openapi/agenta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agenta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agenta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Agenta Testsets API

Create, query, version, and import or export the testsets (evaluation datasets) used to drive evaluations, including CSV/JSON file upload and download.

- **Human URL:** [https://docs.agenta.ai/reference/api/testsets](https://docs.agenta.ai/reference/api/testsets)
- **Base URL:** `https://cloud.agenta.ai/api`

#### Tags

- Testsets
- Datasets
- Evaluation

#### Properties

- [Documentation](https://docs.agenta.ai/evaluation/create-test-sets)
- [API Reference](https://docs.agenta.ai/reference/api/testsets)
- [OpenAPI](openapi/agenta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agenta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agenta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Agenta Observability and Traces API

Ingest LLM telemetry over the OpenTelemetry OTLP/HTTP endpoint and query traces and spans for analytics, sessions, and users. Powers Agenta's LLM observability for cost, latency, and quality monitoring.

- **Human URL:** [https://docs.agenta.ai/observability/overview](https://docs.agenta.ai/observability/overview)
- **Base URL:** `https://cloud.agenta.ai/api`

#### Tags

- Observability
- Traces
- OpenTelemetry

#### Properties

- [Documentation](https://docs.agenta.ai/observability/overview)
- [API Reference](https://docs.agenta.ai/reference/api/traces)
- [OpenAPI](openapi/agenta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agenta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agenta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Agenta-AI)
- [LinkedIn](https://www.linkedin.com/company/agenta-ai)
- [Website](https://agenta.ai/)
- [Documentation](https://docs.agenta.ai/)
- [Plans](plans/agenta-plans-pricing.yml)
- [Rate Limits](rate-limits/agenta-rate-limits.yml)
- [Fin Ops](finops/agenta-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
