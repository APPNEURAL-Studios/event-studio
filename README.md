# Event Studio

Ticketing, agendas and virtual events

Build event pages, ticketing, and agendas for in-person, virtual, and hybrid events. Manage speakers, sponsors, registration, and check-in, design badges and seating charts, run live polls and livestreams, and send post-event surveys.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (9):**

| Service | Status |
|---|---|
| `scheduling-service` | New (Tier-1) |
| `commerce-service` | Core |
| `order-service` | Core |
| `payment-service` | Core |
| `customer-service` | Core |
| `marketing-service` | Core |
| `location-service` | New (Tier-1) |
| `media-service` | New (Tier-1) |
| `publishing-service` | Core |
