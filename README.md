# Alaska Airlines (alaska-air)
Alaska Air Group is the parent company of Alaska Airlines and Horizon Air, providing passenger and cargo air transportation throughout the United States, Mexico, Canada, Costa Rica, and Belize. Alaska Airlines offers a developer portal at developers.alaskaair.com for accessing flight status, schedules, and other APIs, and operates Alaska Air Cargo serving 115+ destinations worldwide with dedicated cargo aircraft.

**URL:** [https://developers.alaskaair.com/](https://developers.alaskaair.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Airlines, Aviation, Travel, Cargo, Loyalty, Flight Status

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Alaska Airlines Flight Status API
The Alaska Airlines Flight Status API provides real-time flight status, departure and arrival information, gate assignments, and delay details for Alaska Airlines (AS) and Horizon Air (QX) flights.

**Human URL:** [https://developers.alaskaair.com/](https://developers.alaskaair.com/)

#### Tags:

 - Flight Status, Aviation, Real-Time Data

#### Properties

- [Documentation](https://developers.alaskaair.com/)
- [APIReference](https://developers.alaskaair.com/)
- [OpenAPI](openapi/alaska-air-flight-status-openapi.yaml)

### Alaska Airlines Flight Schedules API
The Alaska Airlines Flight Schedules API provides access to flight schedule data including route information, operating days, departure and arrival times, and equipment information across the Alaska Airlines and Horizon Air networks.

**Human URL:** [https://developers.alaskaair.com/](https://developers.alaskaair.com/)

#### Tags:

 - Schedules, Aviation, Itinerary

#### Properties

- [Documentation](https://developers.alaskaair.com/)
- [OpenAPI](openapi/alaska-air-flight-schedules-openapi.yaml)

### Alaska Air Cargo API
Alaska Air Cargo APIs enable partners to book shipments, track cargo, get rate estimates, and access schedules across 115+ cargo destinations worldwide. Alaska Airlines operates the only U.S. passenger airline with dedicated cargo aircraft including Airbus A330s and Boeing 787s.

**Human URL:** [https://www.alaskacargo.com/](https://www.alaskacargo.com/)

#### Tags:

 - Cargo, Freight, Shipping, Tracking

#### Properties

- [Documentation](https://www.alaskacargo.com/)
- [Portal](https://www.alaskacargo.com/)
- [OpenAPI](openapi/alaska-air-cargo-openapi.yaml)

### Alaska Airlines Mileage Plan API
The Alaska Mileage Plan partner API enables airline partners, hotel chains, car rental companies, and other loyalty partners to report and redeem miles for members. Alaska's Mileage Plan is consistently rated among the top frequent flyer programs.

**Human URL:** [https://www.alaskaair.com/content/mileage-plan](https://www.alaskaair.com/content/mileage-plan)

#### Tags:

 - Loyalty, Mileage Plan, Rewards, Partners

#### Properties

- [Documentation](https://www.alaskaair.com/content/mileage-plan)
- [OpenAPI](openapi/alaska-air-mileage-plan-openapi.yaml)

## Common Properties

- [Website](https://www.alaskaair.com)
- [Portal](https://developers.alaskaair.com/)
- [Documentation - Alaska Air Cargo Portal](https://www.alaskacargo.com/)

## Features

| Name | Description |
|------|-------------|
| Real-Time Flight Status | Track live flight status, departure and arrival times, gate assignments, and delay information for Alaska Airlines and Horizon Air flights. |
| Flight Schedules | Access flight schedule data including routes, operating days, departure/arrival times, and equipment across the Alaska network. |
| Cargo Booking and Tracking | Book shipments and track cargo across 115+ destinations worldwide via Alaska Air Cargo's network, including dedicated widebody aircraft. |
| Cargo Rate Estimates | Get real-time rate estimates for cargo shipments based on origin, destination, weight, dimensions, and special handling requirements. |
| Mileage Plan Partner Integration | Enable partner mile accrual and redemption for Alaska's Mileage Plan loyalty program across airline, hotel, car rental, and retail partners. |
| Dedicated Cargo Aircraft | Alaska Air Cargo operates the only U.S. passenger airline with dedicated cargo aircraft (Airbus A330s and Boeing 787s) for increased capacity on key routes. |
| Specialized Cargo Services | Support for dangerous goods transport, live animal shipments via Pet Connect, and international cargo across Asia, Pacific, Canada, and Mexico. |
| API Management via Azure | Developer portal powered by Microsoft Azure API Management with subscription-based key management, interactive API console, and automatic API documentation generation. |

## Use Cases

| Name | Description |
|------|-------------|
| Travel Agent and OTA Integration | Integrate Alaska Airlines flight schedules and status into online travel agencies and booking platforms for real-time availability and status updates. |
| Cargo Partner Booking | Enable freight forwarders and cargo brokers to book shipments, get rate quotes, and track Alaska Air Cargo shipments programmatically. |
| Loyalty Partner Mile Reporting | Integrate Mileage Plan mile accrual into partner platforms (hotels, car rentals, credit cards) to automatically report earned miles. |
| Airport Operations Display | Power airport operations systems and display boards with real-time Alaska Airlines flight status and gate assignment data. |
| Corporate Travel Management | Integrate Alaska Airlines flight data into corporate travel management systems for booking, tracking, and expense reporting. |
| Mobile App Integration | Embed Alaska Airlines flight status and schedule data into third-party mobile applications for travelers. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Azure API Management | Developer portal and API gateway powered by Azure API Management with subscription key management and interactive testing console. |
| Hawaiian Airlines | Alaska Air Cargo partnerships including connections with Hawaiian Airlines cargo network for Pacific and inter-island routes. |
| One World Alliance | Member of the oneworld airline alliance enabling Mileage Plan accrual and redemption across 13 member airlines. |
| Duffel | Third-party travel API provider enabling search, booking, and ticket issuance for Alaska Airlines flights. |
| Five9 | Customer service platform integration for Alaska Air Cargo live chat and support operations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Alaska Airlines Flight Status API](openapi/alaska-air-flight-status-openapi.yaml)
- [Alaska Airlines Flight Schedules API](openapi/alaska-air-flight-schedules-openapi.yaml)
- [Alaska Air Cargo API](openapi/alaska-air-cargo-openapi.yaml)
- [Alaska Airlines Mileage Plan API](openapi/alaska-air-mileage-plan-openapi.yaml)

### JSON Schema

- [alaska-air-flight-status-flight-status-schema.json](json-schema/alaska-air-flight-status-flight-status-schema.json)
- [alaska-air-flight-status-flight-list-schema.json](json-schema/alaska-air-flight-status-flight-list-schema.json)
- [alaska-air-flight-schedules-schedule-schema.json](json-schema/alaska-air-flight-schedules-schedule-schema.json)
- [alaska-air-flight-schedules-airport-info-schema.json](json-schema/alaska-air-flight-schedules-airport-info-schema.json)
- [alaska-air-cargo-shipment-schema.json](json-schema/alaska-air-cargo-shipment-schema.json)
- [alaska-air-cargo-shipment-tracking-schema.json](json-schema/alaska-air-cargo-shipment-tracking-schema.json)
- [alaska-air-cargo-rate-response-schema.json](json-schema/alaska-air-cargo-rate-response-schema.json)
- [alaska-air-mileage-plan-member-schema.json](json-schema/alaska-air-mileage-plan-member-schema.json)
- [alaska-air-mileage-plan-transaction-schema.json](json-schema/alaska-air-mileage-plan-transaction-schema.json)

### JSON Structure

- [alaska-air-flight-status-flight-status-structure.json](json-structure/alaska-air-flight-status-flight-status-structure.json)
- [alaska-air-cargo-shipment-structure.json](json-structure/alaska-air-cargo-shipment-structure.json)
- [alaska-air-mileage-plan-member-structure.json](json-structure/alaska-air-mileage-plan-member-structure.json)

### JSON-LD

- [alaska-air-context.jsonld](json-ld/alaska-air-context.jsonld)

### Examples

- [alaska-air-flight-status-flight-status-example.json](examples/alaska-air-flight-status-flight-status-example.json)
- [alaska-air-cargo-shipment-example.json](examples/alaska-air-cargo-shipment-example.json)
- [alaska-air-mileage-plan-member-example.json](examples/alaska-air-mileage-plan-member-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Alaska Airlines Flight Status API](capabilities/shared/flight-status-api.yaml) — 2 operations for flight status and route listing
- [Alaska Air Cargo API](capabilities/shared/cargo-api.yaml) — 4 operations for shipment booking, tracking, and rate estimation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Travel Operations](capabilities/travel-operations.yaml) | alaska-flight-status, alaska-cargo | 5 | Travel Agent, Freight Forwarder, Corporate Travel Manager |

## Vocabulary

- [Alaska Airlines Vocabulary](vocabulary/alaska-air-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Alaska Airlines Spectral Rules](rules/alaska-air-spectral-rules.yml) — 29 rules across 10 categories enforcing Alaska Airlines API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
