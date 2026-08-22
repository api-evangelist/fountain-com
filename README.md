# Fountain (fountain-com)

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
