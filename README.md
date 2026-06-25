# EV Connect (ev-connect)

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
