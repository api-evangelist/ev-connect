# EV Connect (ev-connect)

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

EV Connect is an EV charging network and charge-station management platform (a CPMS / charge point management system) now part of Schneider Electric. Its API Platform exposes open, standards-based APIs through an API Gateway so operators can white-label driver apps and integrate charging into commerce, loyalty, fleet, and energy systems, backed by OCPP station certification and OCPI roaming. Developer documentation and credentials are partner/sales-gated; no public base URL, endpoints, or authentication details are published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ev-connect/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ev-connect/refs/heads/main/apis.yml)

## Tags

- EV Charging
- Charge Point Management
- CPMS
- Mobility
- Energy
- OCPP
- OCPI

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### EV Connect Stations / Charge Points API

Manage charging stations and charge points (EVSE) - registration, status, health, and availability - within the EV Connect charge point management platform. Endpoints and base URL are not publicly documented; access is partner/sales-gated via the EV Connect API Gateway.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Stations
- Charge Points
- EVSE

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Connect Sessions API

Start, stop, and retrieve charging sessions and transaction records, including energy delivered and usage tracked in real time. Endpoints and base URL are not publicly documented; access is partner/sales-gated via the EV Connect API Gateway.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Sessions
- Charging
- Transactions

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Connect Connectors API

Inspect connectors on a charge point - type, power level, and live availability/status. Endpoints and base URL are not publicly documented; access is partner/sales-gated via the EV Connect API Gateway.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Connectors
- EVSE
- Availability

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Connect Drivers API

Manage drivers and their charging accounts, enabling custom driver apps, coupons pushed at plug-in, and loyalty-program tie-ins. Endpoints and base URL are not publicly documented; access is partner/sales-gated via the EV Connect API Gateway.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Drivers
- Accounts
- Loyalty

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Connect Pricing / Plans API

Configure charging pricing, tariffs, and payment handling that govern how sessions are billed across a network. Endpoints and base URL are not publicly documented; access is partner/sales-gated via the EV Connect API Gateway.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Pricing
- Plans
- Payments

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Connect Webhooks

Event notifications for charging lifecycle changes (e.g., session start, stop, and station status). EV Connect markets event-driven integrations, but no public webhook event catalog or payloads are documented; access is partner/sales-gated.

- **Human URL:** [https://www.evconnect.com/platform/](https://www.evconnect.com/platform/)

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.evconnect.com/platform/)
- [OpenAPI](openapi/ev-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ev-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ev-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/evconnect)
- [LinkedIn](https://www.linkedin.com/company/ev-connect)
- [Website](https://www.evconnect.com)
- [Documentation](https://www.evconnect.com/platform/)
- [Plans](plans/ev-connect-plans-pricing.yml)
- [Rate Limits](rate-limits/ev-connect-rate-limits.yml)
- [Fin Ops](finops/ev-connect-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
