# Resurface

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

Resurface (now Graylog API Security) is an API runtime security and observability platform that captures and analyzes complete API request and response payloads in real time. It provides full API call logging, threat detection, data leak prevention, and compliance auditing for API traffic without sampling or aggregation. Resurface was acquired by Graylog and integrated into the Graylog SIEM platform.

**URL:** [https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/resurface/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- API Analytics, API Compliance, API Logging, API Observability, API Security, Data Leak Prevention, Runtime Security, SIEM, Threat Detection

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-02

## APIs

### Resurface Platform

Resurface captures complete API request and response data in real time, providing full-payload API call logging with no sampling. Security teams use it to detect threats, identify data leaks, and ensure compliance across all API traffic using a custom columnar database and SQL query interface.

**Human URL:** [https://resurface.io](https://resurface.io)

#### Tags

- API Compliance, API Logging, API Observability, API Security, Runtime Security, Threat Detection

#### Properties

- [Documentation](https://resurface.io/docs)
- [Getting Started](https://resurface.io/docs/getting-started)
- [Helm Chart](https://artifacthub.io/packages/helm/resurfaceio/resurface)
- [GitHub](https://github.com/resurfaceio)

### Resurface Logger for Go

Open-source Go library for logging API requests and responses to the Resurface database. Supports gorilla/mux and other Go HTTP frameworks.

**Human URL:** [https://github.com/resurfaceio/logger-go](https://github.com/resurfaceio/logger-go)

### Resurface Logger for eBPF

eBPF-based kernel-level API call logger enabling zero-instrumentation API observability for containerized environments.

**Human URL:** [https://github.com/resurfaceio/logger-ebpf](https://github.com/resurfaceio/logger-ebpf)

### Resurface Containers

Official Helm charts and container images for deploying Resurface on Kubernetes.

**Human URL:** [https://resurfaceio.github.io/containers/](https://resurfaceio.github.io/containers/)

### Resurface Trino Connector

Connector for querying Resurface API call data via Trino distributed SQL query engine.

**Human URL:** [https://github.com/resurfaceio/trino-connector](https://github.com/resurfaceio/trino-connector)

## Artifacts

### JSON Schemas

- [`json-schema/resurface-api-call-log-schema.json`](json-schema/resurface-api-call-log-schema.json) — Schema for Resurface API call log records.

### JSON Structure

- [`json-structure/resurface-api-call-log-structure.json`](json-structure/resurface-api-call-log-structure.json) — Structure documenting Resurface entities, export formats, and logger integrations.

### JSON-LD Context

- [`json-ld/resurface-context.jsonld`](json-ld/resurface-context.jsonld) — JSON-LD context mapping Resurface API security vocabulary to schema.org.

### Vocabulary

- [`vocabulary/resurface-vocabulary.yml`](vocabulary/resurface-vocabulary.yml) — Domain vocabulary covering 14 key API security and observability terms.

## Links

- **Website**: [resurface.io](https://resurface.io)
- **Documentation**: [resurface.io/docs](https://resurface.io/docs)
- **GitHub Organization**: [github.com/resurfaceio](https://github.com/resurfaceio)
- **Helm Chart**: [artifacthub.io/packages/helm/resurfaceio/resurface](https://artifacthub.io/packages/helm/resurfaceio/resurface)
- **Acquired By**: [Graylog](https://graylog.org)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
