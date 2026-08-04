# Vitess (vitess)

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

Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable for running large-scale MySQL deployments on Kubernetes or other container orchestration platforms.

**APIs.json:** [https://vitess.io](https://vitess.io)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- CNCF
- Database
- Distributed Systems
- Graduated
- MySQL
- Sharding

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### Vitess VTGate API

VTGate is the stateless proxy that routes queries to the appropriate VTTablet instances. It exposes a MySQL-compatible interface and a gRPC API that clients use to interact with the Vitess cluster, handling query routing, scatter queries, and transaction management across shards.

- **Human URL:** [https://vitess.io/docs/reference/programs/vtgate/](https://vitess.io/docs/reference/programs/vtgate/)

#### Tags

- gRPC
- MySQL
- Proxy
- Query Routing
- SQL

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtgate/)
- [Reference](https://vitess.io/docs/reference/query-serving/)

### Vitess VTAdmin API

VTAdmin is the administrative web application and REST API for managing Vitess clusters. It provides endpoints for inspecting cluster topology, tablets, keyspaces, shards, schemas, and VReplication workflows, and serves as the backend for the VTAdmin web UI.

- **Human URL:** [https://vitess.io/docs/reference/programs/vtadmin/](https://vitess.io/docs/reference/programs/vtadmin/)

#### Tags

- Administration
- Cluster Management
- REST
- Web UI

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtadmin/)
- [Reference](https://vitess.io/docs/reference/vtadmin/)
- [OpenAPI](openapi/vitess-vtadmin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Vitess VTCtld API

VTCtld is the Vitess topology management daemon that exposes a gRPC and HTTP API for administrative operations on the cluster topology including creating and managing keyspaces, shards, tablets, and executing maintenance operations such as planned reparents and emergency reparents.

- **Human URL:** [https://vitess.io/docs/reference/programs/vtctld/](https://vitess.io/docs/reference/programs/vtctld/)

#### Tags

- Administration
- Cluster Management
- gRPC
- Topology

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtctld/)
- [Reference](https://vitess.io/docs/reference/vtctl/)

### Vitess VReplication API

VReplication is the Vitess framework for replicating and transforming data streams within and across Vitess clusters. It powers features such as MoveTables, Reshard, Materialize, and CreateLookupVindex and exposes workflow management commands through the VTCtl API for orchestrating data migrations and real-time replication workflows.

- **Human URL:** [https://vitess.io/docs/reference/vreplication/](https://vitess.io/docs/reference/vreplication/)

#### Tags

- Data Migration
- Replication
- Streaming
- Workflows

#### Properties

- [Documentation](https://vitess.io/docs/reference/vreplication/)
- [Reference](https://vitess.io/docs/reference/vreplication/vreplication/)

## Common Properties

- [JSON Schema](json-schema/vitess-topology-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vitess-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Structure](json-structure/vitess-tablet-structure.json)
- [OpenAPI](openapi/vitess-vtadmin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](rules/vitess-rules.yml)
- [Vocabulary](vocabulary/vitess-vocabulary.yml)
- [Website](https://vitess.io)
- [Documentation](https://vitess.io/docs/)
- [Getting Started](https://vitess.io/docs/get-started/)
- [GitHub Organization](https://github.com/vitessio)
- [GitHub Repository](https://github.com/vitessio/vitess)
- [Blog](https://vitess.io/blog/)
- [Community](https://vitess.io/community/)
- [Slack](https://vitess.io/slack)
- [Changelog](https://github.com/vitessio/vitess/blob/main/changelog/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vitess)
- [Security](https://github.com/vitessio/vitess/blob/main/SECURITY.md)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
