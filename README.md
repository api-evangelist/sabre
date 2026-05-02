# Sabre

Sabre Corporation is a leading technology provider for the global travel industry, operating one of the world's largest travel marketplaces through its Global Distribution System (GDS). Sabre provides APIs for air shopping, booking, hotel reservations, car rentals, rail ticketing, and travel agency workflow automation.

**URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

## APIs

### Sabre Bargain Finder Max API
Low-fare search capabilities for air shopping, returning optimal flight itineraries across Sabre's global airline content inventory including ATPCO, LCC, and NDC content.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Airlines, GDS, Air Shopping, REST

#### Properties
- [Documentation](https://developer.sabre.com/)
- [OpenAPI](openapi/sabre-bargain-finder-max-openapi.yml)

### Sabre Air Booking API
Flight booking, PNR creation, seat selection, ticketing, and booking modification for travel agencies and OTAs.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Airlines, GDS, Booking, PNR, REST

#### Properties
- [Documentation](https://developer.sabre.com/)
- [SDKs](https://github.com/SabreDevStudio/postman-collections)

### Sabre Hotels API
Hotel search, availability, rate shopping, content retrieval, and booking APIs covering over 2 million properties via Sabre GDS and SynXis distribution.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Hotels, GDS, Booking, REST

#### Properties
- [Documentation](https://developer.sabre.com/)
- [SDKs](https://github.com/SabreDevStudio/get-hotel-avail-v2-sample-nodejs)
- [OpenAPI](openapi/sabre-hotels-openapi.yml)

### Sabre Cars API
Car rental search, availability, rate shopping, and reservation management connecting to 40+ brands at 40,000 locations.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Car Rental, GDS, Booking, REST

### Sabre Destination Content API
Destination guides, points of interest, geo data, and travel inspiration content for itinerary planning.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Destination, Content, REST

### Sabre Booking Management API
Unified management of multi-segment travel reservations including flights, hotels, and car rentals.

**Human URL:** [https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management](https://developer.sabre.com/docs/rest_apis/trip/orders/booking_management)

#### Tags
- Travel, Booking, GDS, REST

### Sabre Rail API
Rail ticket search and booking connecting to 30+ rail operators worldwide.

**Human URL:** [https://developer.sabre.com/](https://developer.sabre.com/)

#### Tags
- Travel, Rail, GDS, Booking

## Common Properties

- [Portal](https://developer.sabre.com/)
- [Documentation](https://developer.sabre.com/)
- [GettingStarted](https://developer.sabre.com/guides/travel-agency/api-self-service-guide)
- [Authentication](https://developer.sabre.com/guides/travel-agency/developer-guides/rest-apis-token-credentials)
- [Website](https://www.sabre.com/)
- [Support](https://developer.sabre.com/support)
- [Blog](https://developer.sabre.com/blog)
- [GitHubOrganization](https://github.com/SabreDevStudio)
- [SpectralRules](rules/sabre-rules.yml)
- [JSONSchema](json-schema/sabre-itinerary-schema.json)
- [JSONSchema](json-schema/sabre-hotel-schema.json)
- [JSONLDContext](json-ld/sabre-context.jsonld)
- [Vocabulary](vocabulary/sabre-vocabulary.yml)
- [Capabilities](capabilities/travel-booking.yaml)

## Capabilities

### Shared Definitions
- [sabre-bargain-finder-max](capabilities/shared/sabre-bargain-finder-max.yaml) — Sabre Bargain Finder Max Air Shopping API
- [sabre-hotels](capabilities/shared/sabre-hotels.yaml) — Sabre Hotels Search and Booking API

### Workflows
- [travel-booking](capabilities/travel-booking.yaml) — End-to-end travel booking workflow combining air fare search and hotel booking (7 MCP tools)

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/sabre-bargain-finder-max-openapi.yml](openapi/sabre-bargain-finder-max-openapi.yml) |
| OpenAPI | [openapi/sabre-hotels-openapi.yml](openapi/sabre-hotels-openapi.yml) |
| Spectral Rules | [rules/sabre-rules.yml](rules/sabre-rules.yml) |
| JSON Schema | [json-schema/sabre-itinerary-schema.json](json-schema/sabre-itinerary-schema.json) |
| JSON Schema | [json-schema/sabre-hotel-schema.json](json-schema/sabre-hotel-schema.json) |
| JSON Structure | [json-structure/sabre-air-itinerary-structure.json](json-structure/sabre-air-itinerary-structure.json) |
| JSON-LD Context | [json-ld/sabre-context.jsonld](json-ld/sabre-context.jsonld) |
| Vocabulary | [vocabulary/sabre-vocabulary.yml](vocabulary/sabre-vocabulary.yml) |
| Examples | [examples/](examples/) |

## Maintainers

**Email:** kin@apievangelist.com
