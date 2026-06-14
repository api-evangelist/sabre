# Sabre GraphQL Schema

## Overview

Sabre Corporation operates one of the world's largest travel Global Distribution Systems (GDS), providing APIs for air shopping, booking, hotel reservations, car rentals, rail ticketing, and travel agency workflow automation. This conceptual GraphQL schema represents the core domain objects and relationships across the Sabre platform, covering the full travel commerce lifecycle from search and shopping through booking, ticketing, and post-sale servicing.

The Sabre developer platform is available at https://developer.sabre.com/ and provides REST APIs for travel agencies, airlines, hotels, car rental companies, and online travel agencies (OTAs).

## Schema Source

This schema is a conceptual representation derived from Sabre's public developer documentation, API reference materials, and GDS domain knowledge. It is not an official Sabre-published GraphQL schema but rather a structured model of the Sabre travel commerce domain intended for integration planning, data mapping, and API exploration.

## Domain Coverage

### Air Travel
- Flight search and availability (Bargain Finder Max)
- Seat maps and cabin availability
- Fare shopping, rules, and basis codes
- Flight segments and itinerary construction
- Airline and airport reference data
- Schedule information

### Passenger Name Records (PNR)
- PNR creation, retrieval, and modification
- Traveler and passenger profiles
- Document management (passports, visas)
- Frequent flyer program integration
- Contact information management

### Booking and Ticketing
- Booking creation and management
- Ticket issuance and status tracking
- Electronic Miscellaneous Documents (EMD)
- Ancillary services and seat selection
- Baggage allowances and fees

### Hotel
- Hotel search and availability
- Rate plans and room types
- Property details and amenities
- Hotel booking and modification

### Car Rental
- Car availability and rate shopping
- Rental rate structures
- Car reservation management

### Payment and Services
- Payment method processing
- Service fee management
- Ancillary service catalog

### Agency and Session Management
- API authentication and token management
- Session management
- Queue processing
- Agent profiles and permissions

## Type Index

| Type | Description |
|------|-------------|
| PNR | Passenger Name Record root object |
| PNRDetails | Extended PNR information and segments |
| PNRStatus | Status codes for PNR lifecycle |
| Booking | Travel booking container |
| BookingDetails | Full booking information with segments |
| BookingStatus | Booking lifecycle status |
| Flight | Air flight reference |
| FlightDetails | Detailed flight information |
| FlightOffer | Priced flight itinerary offer |
| FlightSegment | Individual flight leg |
| SegmentDetails | Extended segment information |
| AirAvailability | Seat/cabin availability response |
| SeatMap | Cabin layout with seat inventory |
| Fare | Base fare object |
| FareDetails | Complete fare breakdown |
| FareRules | Conditions and restrictions |
| FareBasis | Fare basis code definition |
| Traveler | Traveler identity object |
| TravelerDetails | Full traveler profile |
| FrequentFlyerDetails | Loyalty program membership |
| Passenger | Passenger in booking context |
| PassengerType | Passenger category (ADT, CHD, INF) |
| PassengerDetails | Passenger-specific booking data |
| ContactInfo | Phone, email, address contact |
| Document | Travel document reference |
| DocumentDetails | Passport, visa, ID details |
| Hotel | Hotel property reference |
| HotelDetails | Full property information |
| HotelRates | Available hotel rate response |
| RoomType | Room category and features |
| RatePlan | Hotel pricing plan |
| Car | Car rental reference |
| CarDetails | Vehicle details and features |
| CarRates | Car rental rate response |
| RentalRate | Specific rental pricing |
| Cruise | Cruise itinerary reference |
| CruiseDetails | Cruise voyage details |
| Package | Travel package reference |
| PackageDetails | Package components and pricing |
| TicketDetails | E-ticket information |
| TicketStatus | Ticket lifecycle status |
| EMD | Electronic Miscellaneous Document |
| EMDDetails | EMD coupon and service details |
| Payment | Payment transaction reference |
| PaymentDetails | Full payment record |
| PaymentMethod | Payment instrument definition |
| ServiceDetails | Travel service information |
| AncillaryService | Add-on service (seat, bag, meal) |
| SeatDetails | Individual seat attributes |
| BaggageDetails | Baggage allowance and fees |
| Airport | Airport reference data |
| AirportDetails | Full airport information |
| Airline | Carrier reference data |
| AirlineDetails | Full airline information |
| Schedule | Flight schedule reference |
| ScheduleDetails | Full schedule data |
| Queue | PNR queue reference |
| QueueDetails | Queue contents and management |
| Profile | Agency/traveler profile |
| ProfileDetails | Full profile data |
| MemberDetails | Loyalty program member record |
| APIKey | API credential reference |
| Token | OAuth access token |
| Session | Sabre session reference |
| SessionToken | Session authentication token |

## Key Relationships

- A **Booking** contains one or more **FlightSegment**, **Hotel**, or **Car** records
- A **PNR** is associated with one or more **Passenger** records and **FlightSegment** records
- A **FlightOffer** contains **FlightSegment** records and a **Fare**
- A **Fare** has associated **FareRules** and **FareBasis** codes
- A **Traveler** may have multiple **Document** records and **FrequentFlyerDetails**
- An **AncillaryService** is associated with a **FlightSegment** and **Passenger**
- A **TicketDetails** is linked to a **Booking** and one or more **PassengerDetails**
- A **Session** holds a **SessionToken** and is scoped to an **APIKey**

## Usage Notes

- Sabre uses OAuth 2.0 token-based authentication for REST APIs
- PNR is the central record-keeping unit in GDS-based travel bookings
- NDC (New Distribution Capability) content is supported alongside traditional ATPCO fares
- Sabre's Bargain Finder Max API is the primary air shopping entry point
- Queue management is used by travel agencies to process PNRs requiring attention
