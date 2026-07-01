# Fountain (fountain-com)

Fountain is a high-volume, frontline hourly hiring and workforce management platform used by enterprises to source, screen, schedule, and hire large numbers of hourly workers. The Fountain Developer API (Hire API v2) lets customers programmatically manage applicants, openings (funnels), positions, stages, labels, secure documents, interview scheduling slots, webhooks, and post-hire workers across their hiring funnels. All requests use the `https://api.fountain.com/v2` base URL and authenticate with an API token passed in the `X-ACCESS-TOKEN` request header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fountain-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fountain-com/refs/heads/main/apis.yml)

## Tags

- Hiring
- Recruiting
- Applicant Tracking
- Frontline Hiring
- Hourly Workforce
- HR Tech
- Onboarding

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Fountain Applicants API

Create, list, retrieve, update, delete, and advance applicants through hiring funnels, plus notify applicants, pull transition history, and look up duplicate applicants.

- **Human URL:** [https://developer.fountain.com/reference/applicants](https://developer.fountain.com/reference/applicants)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Applicants
- Candidates
- Applicant Tracking

#### Properties

- [Documentation](https://developer.fountain.com/reference/applicants)
- [API Reference](https://developer.fountain.com/reference/get_v2-applicants)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Openings API

Manage openings (funnels) - the hiring workflows candidates move through - including listing, creating, updating, deleting openings, and listing the stages that belong to each opening.

- **Human URL:** [https://developer.fountain.com/reference/openings](https://developer.fountain.com/reference/openings)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Openings
- Funnels
- Jobs

#### Properties

- [Documentation](https://developer.fountain.com/reference/openings)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Positions API

List, retrieve, create, update, and delete positions - the job roles applicants are hired into - and assign company attributes to them.

- **Human URL:** [https://developer.fountain.com/reference/positions](https://developer.fountain.com/reference/positions)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Positions
- Roles

#### Properties

- [Documentation](https://developer.fountain.com/reference/positions)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Stages API

Retrieve individual stages within an opening and list the available scheduling slots attached to a stage as applicants progress.

- **Human URL:** [https://developer.fountain.com/reference/stages](https://developer.fountain.com/reference/stages)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Stages
- Workflow

#### Properties

- [Documentation](https://developer.fountain.com/reference/stages)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Scheduling API

Create, list, update, and delete calendar / interview slots, and book or cancel booked slots for applicant interview sessions.

- **Human URL:** [https://developer.fountain.com/reference/available-slots](https://developer.fountain.com/reference/available-slots)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Scheduling
- Interviews
- Slots

#### Properties

- [Documentation](https://developer.fountain.com/reference/available-slots)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Labels API

List, assign, and remove labels on applicants and enumerate all labels used within a given stage for automated screening and routing.

- **Human URL:** [https://developer.fountain.com/reference/labels](https://developer.fountain.com/reference/labels)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Labels
- Tagging

#### Properties

- [Documentation](https://developer.fountain.com/reference/labels)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Documents API

Retrieve, upload, link, and approve secure applicant documents, including direct-to-S3 upload flows and document approval for compliance.

- **Human URL:** [https://developer.fountain.com/reference/secure-documents](https://developer.fountain.com/reference/secure-documents)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Documents
- Secure Documents
- Files

#### Properties

- [Documentation](https://developer.fountain.com/reference/secure-documents)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Webhooks API

List, create, retrieve, and delete webhook settings so external systems receive real-time notifications of applicant and hiring events.

- **Human URL:** [https://developer.fountain.com/reference/webhooks](https://developer.fountain.com/reference/webhooks)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developer.fountain.com/reference/webhooks)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fountain Workers API

List, retrieve, update, activate, and deactivate hired workers for post-hire workforce management across the Fountain product suite.

- **Human URL:** [https://developer.fountain.com/reference/workers](https://developer.fountain.com/reference/workers)
- **Base URL:** `https://api.fountain.com/v2`

#### Tags

- Workers
- Workforce Management
- Post-Hire

#### Properties

- [Documentation](https://developer.fountain.com/reference/workers)
- [OpenAPI](openapi/fountain-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fountain-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fountain-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/fountaininc)
- [Website](https://www.fountain.com)
- [Documentation](https://developer.fountain.com/reference)
- [Plans](plans/fountain-com-plans-pricing.yml)
- [Rate Limits](rate-limits/fountain-com-rate-limits.yml)
- [Fin Ops](finops/fountain-com-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
