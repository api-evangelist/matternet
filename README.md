# Matternet (matternet)

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

### Matternet Station and Aircraft Telemetry

During flights, M2 drones and Matternet Stations transmit real-time protobuf telemetry to the Matternet cloud over an MQTT broker (HiveMQ). This is an internal device-to-cloud telemetry transport, not a documented public subscribe API; no broker endpoint, topic schema, or credentials are published for third-party developers.

- **Human URL:** [https://www.matternet.com/our-system-landing-station](https://www.matternet.com/our-system-landing-station)

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
