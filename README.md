# Agenta (agenta)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
