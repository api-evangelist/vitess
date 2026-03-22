# Vitess (vitess)
Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable for running large-scale MySQL deployments on Kubernetes or other container orchestration platforms.

**URL:** [Visit APIs.json URL](https://vitess.io)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Database, MySQL, Distributed Systems, Sharding, Cloud Native, Graduated

## Timestamps

- **Created:** 2025 
- **Modified:** 2026-03-18 

## APIs

### Vitess VTGate API
VTGate is the stateless proxy that routes queries to the appropriate VTTablet instances. It exposes a MySQL-compatible interface and a gRPC API that clients use to interact with the Vitess cluster, handling query routing, scatter queries, and transaction management across shards.

**Human URL:** [https://vitess.io/docs/reference/programs/vtgate/](https://vitess.io/docs/reference/programs/vtgate/)


#### Tags:

 - SQL, Query Routing, MySQL, gRPC, Proxy

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtgate/)
- [Reference](https://vitess.io/docs/reference/query-serving/)

### Vitess VTAdmin API
VTAdmin is the administrative web application and REST API for managing Vitess clusters. It provides endpoints for inspecting cluster topology, tablets, keyspaces, shards, schemas, and VReplication workflows, and serves as the backend for the VTAdmin web UI.

**Human URL:** [https://vitess.io/docs/reference/programs/vtadmin/](https://vitess.io/docs/reference/programs/vtadmin/)


#### Tags:

 - Administration, REST, Cluster Management, Web UI

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtadmin/)
- [Reference](https://vitess.io/docs/reference/vtadmin/)
- [OpenAPI](openapi/vitess-vtadmin-openapi.yml)

### Vitess VTCtld API
VTCtld is the Vitess topology management daemon that exposes a gRPC and HTTP API for administrative operations on the cluster topology including creating and managing keyspaces, shards, tablets, and executing maintenance operations such as planned reparents and emergency reparents.

**Human URL:** [https://vitess.io/docs/reference/programs/vtctld/](https://vitess.io/docs/reference/programs/vtctld/)


#### Tags:

 - Administration, gRPC, Topology, Cluster Management

#### Properties

- [Documentation](https://vitess.io/docs/reference/programs/vtctld/)
- [Reference](https://vitess.io/docs/reference/vtctl/)

### Vitess VReplication API
VReplication is the Vitess framework for replicating and transforming data streams within and across Vitess clusters. It powers features such as MoveTables, Reshard, Materialize, and CreateLookupVindex and exposes workflow management commands through the VTCtl API for orchestrating data migrations and real-time replication workflows.

**Human URL:** [https://vitess.io/docs/reference/vreplication/](https://vitess.io/docs/reference/vreplication/)


#### Tags:

 - Replication, Data Migration, Streaming, Workflows

#### Properties

- [Documentation](https://vitess.io/docs/reference/vreplication/)
- [Reference](https://vitess.io/docs/reference/vreplication/vreplication/)

## Common Properties

- [JSONSchema](json-schema/vitess-topology-schema.json)
- [JSON-LD](json-ld/vitess-context.jsonld)
- [Website](https://vitess.io)
- [Documentation](https://vitess.io/docs/)
- [Getting Started](https://vitess.io/docs/get-started/)
- [GitHub Organization](https://github.com/vitessio)
- [GitHubRepository](https://github.com/vitessio/vitess)
- [Blog](https://vitess.io/blog/)
- [Community](https://vitess.io/community/)
- [Slack](https://vitess.io/slack)
- [Change Log](https://github.com/vitessio/vitess/blob/main/changelog/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/vitess)
- [Security](https://github.com/vitessio/vitess/blob/main/SECURITY.md)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
