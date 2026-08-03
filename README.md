# Apache NiFi (apache-nifi)

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

Apache NiFi is a dataflow management system designed to automate the flow of data between systems. It provides a web-based user interface for designing, controlling, and monitoring data flows with real-time operational control, data provenance tracking, and support for hundreds of processors. NiFi Version 2 is the current major version with enhanced security and performance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-nifi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-nifi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Integration
- Dataflow
- ETL
- IoT
- Streaming
- Data Pipeline

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache NiFi REST API

The NiFi REST API provides comprehensive JWT-authenticated endpoints for managing processors, connections, controller services, process groups, reporting tasks, provenance, flow versions, system diagnostics, access control, parameter contexts, and data transfer. Base URL is http://nifi-host:8080/nifi-api. OpenAPI spec available at /nifi-docs/swagger.yaml.

- **Human URL:** [https://nifi.apache.org/components/](https://nifi.apache.org/components/)

#### Tags

- Dataflow
- Flow Management
- REST
- JWT

#### Properties

- [Documentation](https://nifi.apache.org/components/)
- [OpenAPI](https://nifi.apache.org/nifi-docs/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://nifi.apache.org/documentation/guides/)
- [GitHub Repository](https://github.com/apache/nifi)
- [Postman Collection](collections/apache-nifi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-nifi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache NiFi Registry

NiFi Registry provides a central location for storage and management of shared NiFi flow resources, enabling versioned flows across NiFi environments. It provides its own REST API for managing buckets, flows, versions, and users.

- **Human URL:** [https://nifi.apache.org/documentation/](https://nifi.apache.org/documentation/)

#### Tags

- Flow Versioning
- Registry
- REST

#### Properties

- [Documentation](https://nifi.apache.org/documentation/)
- [GitHub Repository](https://github.com/apache/nifi)
- [Postman Collection](collections/apache-nifi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-nifi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache MiNiFi

MiNiFi is a lightweight agent for edge data collection that is a subproject of NiFi. MiNiFi C++ (nifi-minifi-cpp) provides a small-footprint agent for IoT edge data collection with local processing and a remote NiFi parent instance for management.

- **Human URL:** [https://nifi.apache.org/minifi/](https://nifi.apache.org/minifi/)

#### Tags

- Edge Computing
- IoT
- Lightweight Agent

#### Properties

- [Documentation](https://nifi.apache.org/minifi/)
- [GitHub Repository](https://github.com/apache/nifi-minifi-cpp)
- [Postman Collection](collections/apache-nifi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-nifi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apache-nifi)
- [Portal](https://nifi.apache.org/)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/nifi)
- [GitHub Repository](https://github.com/apache/nifi-minifi-cpp)
- [GitHub Repository](https://github.com/apache/nifi-api)
- [GitHub Repository](https://github.com/apache/nifi-site)
- [Wiki](https://cwiki.apache.org/confluence/display/NIFI)
- [Issue Tracker](https://issues.apache.org/jira/browse/NIFI)
- [Slack](https://join.slack.com/t/apachenifi/shared_invite/zt-11njbtkdx-ZRU8FKYSWoEHRJetidy0zA)
- [Blog](https://nifi.apache.org/blog/)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
