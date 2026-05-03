# Union Pacific (union-pacific)
Union Pacific is one of the largest freight railroad networks in the United States, operating across 23 states in the western two-thirds of the country. The company transports a diverse range of commodities including agricultural products, automotive goods, chemicals, energy resources, and industrial materials. Union Pacific's API platform gives businesses programmatic access to real-time shipment tracking, equipment management, intermodal planning, and supply chain exception handling, enabling seamless integration with logistics and supply chain management systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Freight, Railroads, Shipping, Trains, Supply Chain, Logistics

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## APIs

### Union Pacific API
The Union Pacific API provides programmatic access to real-time railroad supply chain data and operational actions. The API enables shipment tracking, equipment management, order placement, exception case management, and intermodal planning. APIs are structured as data objects that can be used standalone or combined to create robust supply chain workflows. Authentication uses OAuth 2.0 Client Credentials flow.

**Human URL:** [https://www.up.com/customers/all/api-developer/index.htm](https://www.up.com/customers/all/api-developer/index.htm)

**Base URL:** https://api.up.com

#### Tags

- Freight, Railroads, Shipping, Trains, Supply Chain, Logistics

#### Properties

- [Documentation](https://www.up.com/customers/all/api-developer/index.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/openapi/union-pacific-api.yaml)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/rules/union-pacific-spectral-rules.yml)
- [NaftikoCapability - Shared](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/capabilities/shared/union-pacific-api.yaml)
- [NaftikoCapability - Rail Freight Operations](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/capabilities/rail-freight-operations.yaml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/vocabulary/union-pacific-vocabulary.yaml)
- [JSON-LD Context](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld)

#### JSON Schemas

- [Shipment](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-shipment-schema.json)
- [Case](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-case-schema.json)
- [Equipment](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-equipment-schema.json)
- [Location](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-location-schema.json)
- [Waybill](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-waybill-schema.json)
- [Intermodal Reservation](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-reservation-schema.json)
- [Intermodal Lane](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-lane-schema.json)
- [Intermodal Departure](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-schema/union-pacific-intermodal-departure-schema.json)

#### Examples

- [List Shipments](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/examples/union-pacific-list-shipments-example.json)
- [Create Intermodal Reservation](https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/examples/union-pacific-create-intermodal-reservation-example.json)

## Features

- **Real-Time Shipment Tracking** — Track active rail shipments with current location and estimated arrival times
- **Exception Case Management** — Monitor and resolve supply chain exceptions for off-course or delayed shipments
- **Equipment Management** — Search, order, and release rail car equipment including intermodal containers
- **Intermodal Planning** — Create reservations, find service lanes, and view departure schedules for intermodal transport
- **Network Locations** — Access Union Pacific facility, yard, and terminal location data across the network
- **Waybill Lookup** — Retrieve waybill documents with shipment routing and billing information
- **OAuth 2.0 Security** — Secure API access using OAuth 2.0 Client Credentials flow

## Use Cases

- **Supply Chain Visibility** — Logistics managers monitor active shipments across the UP network in real time
- **Exception Resolution** — Operations teams identify and resolve shipment exceptions to minimize delays
- **Intermodal Logistics** — Shippers book intermodal container space between UP terminals for coast-to-coast transport
- **Equipment Procurement** — Businesses order rail car equipment for upcoming shipping needs
- **Supply Chain Integration** — ERP and TMS platforms integrate UP freight data via API for automated logistics workflows

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
