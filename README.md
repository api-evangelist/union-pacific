# Union Pacific (union-pacific)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
