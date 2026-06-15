# Pi-hole (pi-hole)

Pi-hole is an open source network-wide DNS sinkhole that blocks ads, tracking, and unwanted domains across all devices on a local network without requiring per-device software. It runs on lightweight hardware such as Raspberry Pi and offers a web admin interface plus a REST API (introduced in v6 via the pihole-FTL binary) for programmatic management of blocklists, allowlists, groups, clients, DNS settings, and live query logs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pi-hole/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pi-hole/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- DNS
- Ad Blocking
- Network Security
- Privacy
- Open Source
- Self-Hosted

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Pi-hole REST API

REST API exposed by the pihole-FTL binary (v6+) for managing DNS blocklists, allowlists, groups, clients, configuration, and query logs. Returns JSON, uses standard HTTP verbs and status codes, and requires API key authentication for most endpoints. Self-hosted OpenAPI/Swagger documentation is served by each Pi-hole instance at /api/docs.

- **Human URL:** [https://docs.pi-hole.net/api/](https://docs.pi-hole.net/api/)
- **Base URL:** `http://pi.hole/api`

#### Tags

- DNS
- Ad Blocking
- Network Security
- Privacy
- Self-Hosted

#### Properties

- [Documentation](https://docs.pi-hole.net/api/)
- [OpenAPI](http://pi.hole/api/docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.pi-hole.net/api/auth/)
- [Postman Collection](collections/pi-hole.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pi-hole.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/the-pi-hole)
- [Website](https://pi-hole.net)
- [Documentation](https://docs.pi-hole.net)
- [GitHub Organization](https://github.com/pi-hole)
- [Source  Code](https://github.com/pi-hole/pi-hole)
- [F T L  Source](https://github.com/pi-hole/FTL)
- [Discourse  Forum](https://discourse.pi-hole.net)
- [Donate](https://pi-hole.net/donate/)
- [Blog](https://pi-hole.net/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
