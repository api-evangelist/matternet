# Matternet (matternet)

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

Matternet designs, builds, and operates autonomous urban drone-logistics networks for healthcare and on-demand delivery. The integrated system pairs the FAA type-certified M2 aircraft with the Matternet Station and a proprietary cloud Software Platform that routes, commands, and monitors flights. Telemetry streams from drones and stations to the cloud over an MQTT broker (HiveMQ) as protobuf messages, and a consistent internal Hasura-powered GraphQL data layer serves Matternet's operator and client applications. As of this profile, Matternet does not publish a public or self-serve developer API; integrations are delivered through partner and operator engagements.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/matternet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/matternet/refs/heads/main/apis.yml)

## Tags

- Drone Delivery
- Logistics
- Healthcare
- Autonomous
- UAS
- Telemetry

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Matternet Cloud Software Platform

Matternet's proprietary cloud platform that receives customer delivery requests, generates routes, and commands, controls, and monitors all operating Matternet assets. A consistent internal Hasura-powered GraphQL data layer serves Matternet's operator and client applications (Mission Control, Ground Operations, Management App Suite). No public or self-serve developer API is documented; access is partner/operator-only.

- **Human URL:** [https://www.matternet.com/our-system-software-platform](https://www.matternet.com/our-system-software-platform)

#### Tags

- Cloud Platform
- Dispatch
- Routing
- GraphQL

#### Properties

- [Documentation](https://www.matternet.com/our-system-software-platform)
- [OpenAPI](openapi/matternet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/matternet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matternet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Matternet Logistics Integration

Operator-facing logistics surface for requesting deliveries and tracking payload chain-of-custody across hospital, laboratory, and pharmacy workflows. Matternet has referenced a secure medical drone delivery portal for hospitals, but no public integration API (e.g. LIS/EHR dispatch) is publicly documented. Integration is delivered through partner engagements.

- **Human URL:** [https://www.matternet.com/our-system](https://www.matternet.com/our-system)

#### Tags

- Integration
- Healthcare
- Delivery Portal
- Chain of Custody

#### Properties

- [Documentation](https://www.matternet.com/our-system)
- [OpenAPI](openapi/matternet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/matternet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/matternet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- Telemetry
- MQTT
- Station
- Aircraft

#### Properties

- [Documentation](https://www.matternet.com/our-system-landing-station)
- [Documentation](https://www.matternet.com/our-system-aircraft)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/matternet-inc)
- [Website](https://www.matternet.com/)
- [Documentation](https://www.matternet.com/our-system)
- [Plans](plans/matternet-plans-pricing.yml)
- [Rate Limits](rate-limits/matternet-rate-limits.yml)
- [Fin Ops](finops/matternet-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
