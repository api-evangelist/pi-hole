# Pi-hole (pi-hole)

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
