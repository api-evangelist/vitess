# Vitess (vitess)

Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable for running large-scale MySQL deployments on Kubernetes or other container orchestration platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vitess/refs/heads/main/apis.yml)

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

VTGate is the stateless proxy that routes queries to the appropriate VTTablet instances. It exposes a MySQL-compatible interface and a gRPC API.

**Human URL:** [https://vitess.io/docs/reference/programs/vtgate/](https://vitess.io/docs/reference/programs/vtgate/)

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtgate/)
- [Reference](https://vitess.io/docs/reference/query-serving/)

### Vitess VTAdmin API

VTAdmin is the administrative REST API and web application for managing Vitess clusters, providing endpoints for topology, tablets, keyspaces, schemas, and VReplication workflows.

**Human URL:** [https://vitess.io/docs/reference/programs/vtadmin/](https://vitess.io/docs/reference/programs/vtadmin/)

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtadmin/)
- [Reference](https://vitess.io/docs/reference/vtadmin/)
- [OpenAPI](openapi/vitess-vtadmin-openapi.yml)

### Vitess VTCtld API

VTCtld manages the cluster topology with gRPC and HTTP APIs for keyspace, shard, and tablet operations.

**Human URL:** [https://vitess.io/docs/reference/programs/vtctld/](https://vitess.io/docs/reference/programs/vtctld/)

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtctld/)
- [Reference](https://vitess.io/docs/reference/vtctl/)

### Vitess VReplication API

VReplication powers data movement workflows including MoveTables, Reshard, Materialize, and CreateLookupVindex.

**Human URL:** [https://vitess.io/docs/reference/vreplication/](https://vitess.io/docs/reference/vreplication/)

#### Properties

- [Documentation](https://vitess.io/docs/reference/vreplication/)
- [Reference](https://vitess.io/docs/reference/vreplication/vreplication/)

## Common Properties

- [Website](https://vitess.io)
- [Documentation](https://vitess.io/docs/)
- [Getting Started](https://vitess.io/docs/get-started/)
- [GitHub Organization](https://github.com/vitessio)
- [GitHub Repository](https://github.com/vitessio/vitess)
- [Blog](https://vitess.io/blog/)
- [Community](https://vitess.io/community/)
- [Slack](https://vitess.io/slack)
- [Change Log](https://github.com/vitessio/vitess/blob/main/changelog/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vitess)
- [Security](https://github.com/vitessio/vitess/blob/main/SECURITY.md)

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [openapi/vitess-vtadmin-openapi.yml](openapi/vitess-vtadmin-openapi.yml) |
| JSON Schema | [json-schema/vitess-topology-schema.json](json-schema/vitess-topology-schema.json) |
| JSON Structure | [json-structure/vitess-tablet-structure.json](json-structure/vitess-tablet-structure.json) |
| JSON-LD | [json-ld/vitess-context.jsonld](json-ld/vitess-context.jsonld) |
| Spectral Rules | [rules/vitess-rules.yml](rules/vitess-rules.yml) |
| Vocabulary | [vocabulary/vitess-vocabulary.yml](vocabulary/vitess-vocabulary.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| VTAdmin API | [capabilities/shared/vitess-vtadmin.yaml](capabilities/shared/vitess-vtadmin.yaml) |

### Workflow Capabilities

| Workflow | File | Description |
|----------|------|-------------|
| Cluster Administration | [capabilities/cluster-administration.yaml](capabilities/cluster-administration.yaml) | Unified topology, tablet, schema, workflow, and backup management for Vitess clusters |

## Examples

- [List Tablets](examples/vitess-vtadmin-getTablets-example.json)
- [List Workflows](examples/vitess-vtadmin-getWorkflows-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
