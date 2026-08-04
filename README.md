# Sabre (sabre)

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

Sabre Corporation is a leading technology provider for the global travel industry, operating one of the world's largest travel marketplaces through its Global Distribution System (GDS). Sabre provides APIs for air shopping, booking, hotel reservations, car rentals, rail ticketing, and travel agency workflow automation to airlines, hotels, travel agencies, and online travel agencies (OTAs).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sabre/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Travel
- GDS
- Airlines
- Hotels
- Car Rental
- Booking

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### Sabre Bargain Finder Max API

Sabre Bargain Finder Max (BFM) API provides low-fare search capabilities for air shopping, returning optimal flight itineraries with pricing across Sabre's global airline content inventory including ATPCO, LCC, and NDC content. Supports one-way, round-trip, open-jaw, and multi-city searches with flexible date ranges and cabin preferences.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Airlines
- GDS
- Air Shopping
- REST

#### Properties

- [Documentation](https://developer.sabre.com/)
- [OpenAPI](openapi/sabre-bargain-finder-max-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Air Booking API

Sabre Air Booking API enables flight booking, passenger name record (PNR) creation and management, seat selection, ticketing, and booking modification for travel agencies and online travel applications. Supports NDC offer booking, ancillary services, and PNR queue management.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Airlines
- GDS
- Booking
- PNR
- REST

#### Properties

- [Documentation](https://developer.sabre.com/)
- [S D Ks](https://github.com/SabreDevStudio/postman-collections)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Hotels API

Sabre Hotels API provides hotel search, availability, rate shopping, content retrieval, and booking APIs for travel agencies and OTAs, accessing Sabre's global lodging content covering over 2 million properties and SynXis hotel distribution network. Supports radius search, amenity filters, chain preferences, and cancellation management.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Hotels
- GDS
- Booking
- REST

#### Properties

- [Documentation](https://developer.sabre.com/)
- [S D Ks](https://github.com/SabreDevStudio/get-hotel-avail-v2-sample-nodejs)
- [OpenAPI](openapi/sabre-hotels-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Cars API

Sabre Cars API provides car rental search, availability, rate shopping, reservation, and management APIs for travel agencies and OTAs, connecting to over 40 global car rental brands across 40,000 locations through Sabre's GDS distribution.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Car Rental
- GDS
- Booking
- REST

#### Properties

- [Documentation](https://developer.sabre.com/)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Destination Content API

Sabre Destination Content API provides destination guides, points of interest, geo data, and travel inspiration content for travel applications and itinerary planning tools.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Destination
- Content
- REST

#### Properties

- [Documentation](https://developer.sabre.com/)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Booking Management API

Sabre Booking Management API provides unified management of multi-segment travel reservations including flights, hotels, and car rentals within a single booking record. Supports booking creation, retrieval, modification, and cancellation.

- **Human URL:** [https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management](https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management)

#### Tags

- Travel
- Booking
- GDS
- REST

#### Properties

- [Documentation](https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sabre Rail API

Sabre Rail API provides rail ticket search, booking, and management capabilities connecting to over 30 rail operators worldwide for travel agencies and multi-modal booking platforms.

- **Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags

- Travel
- Rail
- GDS
- Booking

#### Properties

- [Documentation](https://developer.sabre.com/)
- [Postman Collection](collections/sabre-bargain-finder-max.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-bargain-finder-max.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sabre-hotels.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sabre-hotels.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sabre-corporation)
- [Portal](https://developer.sabre.com/)
- [Documentation](https://developer.sabre.com/)
- [Getting Started](https://developer.sabre.com/guides/travel-agency/api-self-service-guide)
- [Authentication](https://developer.sabre.com/guides/travel-agency/developer-guides/rest-apis-token-credentials)
- [Website](https://www.sabre.com/)
- [Support](https://developer.sabre.com/support)
- [Blog](https://developer.sabre.com/blog)
- [GitHub Organization](https://github.com/SabreDevStudio)
- [S D Ks](https://github.com/SabreDevStudio)
- [Spectral Rules](rules/sabre-rules.yml)
- [JSON Schema](json-schema/sabre-itinerary-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sabre-hotel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sabre-air-itinerary-structure.json)
- [JSON Structure](json-structure/sabre-hotel-structure.json)
- [J S O N L D Context](json-ld/sabre-context.jsonld)
- [Vocabulary](vocabulary/sabre-vocabulary.yml)
- [Capabilities](capabilities/travel-booking.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
