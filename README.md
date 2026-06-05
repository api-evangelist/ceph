# Ceph (ceph)

Ceph is an open source, distributed storage platform that provides unified object, block, and file storage on commodity hardware with no single point of failure. The Ceph Manager (ceph-mgr) ships with a RESTful API that exposes the same operations available in the Ceph Dashboard for managing pools, OSDs, hosts, monitors, RGW, RBD, CephFS, and cluster configuration. The API is OpenAPI 3.0 compliant and authenticates via JWT bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ceph/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ceph/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Storage
- Distributed Storage
- Object Storage
- Block Storage
- File Storage
- Open Source
- Software-Defined Storage

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Ceph RESTful API

RESTful API exposed by the Ceph Manager dashboard module for managing and monitoring a Ceph cluster, including pools, OSDs, hosts, monitors, RGW, RBD, CephFS, users, and cluster configuration. Authentication uses a JWT obtained from /api/auth, and versioning is negotiated via the Accept header (application/vnd.ceph.api.v{major}.{minor}+json).

- **Human URL:** [https://docs.ceph.com/en/latest/mgr/ceph_api/](https://docs.ceph.com/en/latest/mgr/ceph_api/)
- **Base URL:** `https://{manager_host}:{dashboard_port}/api`

#### Tags

- Storage
- Cluster Management
- Pools
- OSD
- Monitors
- RGW
- RBD
- CephFS
- JWT

#### Properties

- [Documentation](https://docs.ceph.com/en/latest/mgr/ceph_api/)
- [OpenAPI](https://{manager_host}:{dashboard_port}/docs/api.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger  U I](https://{manager_host}:{dashboard_port}/docs)
- [Source  Code](https://github.com/ceph/ceph)
- [Postman Collection](collections/ceph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ceph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ceph)
- [Website](https://ceph.io)
- [Documentation](https://docs.ceph.com)
- [GitHub Organization](https://github.com/ceph)
- [Mailing  Lists](https://ceph.io/en/community/connect/)
- [Foundation](https://ceph.io/en/foundation/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
