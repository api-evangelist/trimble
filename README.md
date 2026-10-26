# Trimble (trimble)

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

Trimble Inc. is a global technology company that provides advanced positioning, navigation, and data analytics solutions across construction, agriculture, transportation, and geospatial industries. Founded in 1978 as Trimble Navigation Limited, the company integrates GPS, laser, optical, and inertial technologies with software and services. Trimble's developer platform spans construction collaboration (Trimble Connect), commercial vehicle routing (PC*MILER, Trimble Maps), building information modeling (Tekla, SketchUp), fleet management (TruckMate, TMT, CoPilot), precision positioning (Mobile Manager, TAP Store), and construction ERP (Viewpoint). Publicly traded on NASDAQ as TRMB.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Construction
- Transportation
- Geospatial
- GPS
- Mapping
- BIM
- Fleet Management
- Collaboration
- Agriculture

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Trimble Connect API

The Trimble Connect API enables integration with Trimble's cloud-based construction collaboration platform. Provides access to project data, BIM models, document management, issues (BCF Topics), and team collaboration features for construction project management. Acts as the BIM collaboration hub integrating Tekla, SketchUp, and third-party tools.

- **Human URL:** [https://developer.trimble.com/docs/connect](https://developer.trimble.com/docs/connect)

#### Tags

- Construction
- Collaboration
- BIM
- Cloud
- Document Management

#### Properties

- [Documentation](https://developer.trimble.com/docs/connect)
- [OpenAPI](openapi/trimble-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/trimble-rules.yml)
- [JSON Schema](json-schema/trimble-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trimble-project-structure.json)
- [J S O N L D Context](json-ld/trimble-context.jsonld)

### Trimble Maps API

The Trimble Maps API (formerly ALK Technologies PC*MILER) provides interactive mapping and routing solutions optimized for commercial vehicles and transportation. Enables truck-specific routing, geocoding, map tile rendering, and turn-by-turn navigation services across North America, Europe, and global markets.

- **Human URL:** [https://developer.trimble.com/docs/maps](https://developer.trimble.com/docs/maps)

#### Tags

- Mapping
- Transportation
- Routing
- Geospatial
- Commercial Vehicles

#### Properties

- [Documentation](https://developer.trimble.com/docs/maps)
- [Developer Portal](https://developer.trimblemaps.com/)
- [OpenAPI](openapi/trimble-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/trimble-route-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trimble-route-structure.json)

### Trimble PC*MILER API

PC*MILER provides commercial vehicle routing and distance calculation APIs for logistics, freight, and transportation management. Delivers mileage, routing, tolls, and fuel optimization for trucking operations across North America, Europe, and global markets.

- **Human URL:** [https://developer.trimble.com/docs/pc-miler](https://developer.trimble.com/docs/pc-miler)

#### Tags

- Transportation
- Routing
- Logistics
- Distance Calculation
- Commercial Vehicles

#### Properties

- [Documentation](https://developer.trimble.com/docs/pc-miler)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tekla API

The Tekla API provides programmatic access to Tekla Structures, a leading Building Information Modeling (BIM) software for structural engineering and detailing. Enables custom model creation, data extraction, and workflow automation for steel, concrete, and timber construction.

- **Human URL:** [https://developer.tekla.com/](https://developer.tekla.com/)

#### Tags

- BIM
- Structural Engineering
- Construction
- Modeling

#### Properties

- [Documentation](https://developer.tekla.com/)
- [Developer Portal](https://developer.tekla.com/)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SketchUp API

The SketchUp API enables extension development for Trimble SketchUp, a widely-used 3D modeling and design tool. Supports Ruby and JavaScript APIs for building custom tools, plugins, and integrations for architecture, interior design, and engineering workflows.

- **Human URL:** [https://developer.sketchup.com/](https://developer.sketchup.com/)

#### Tags

- 3D Modeling
- Architecture
- Design
- Plugins

#### Properties

- [Documentation](https://developer.sketchup.com/)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ProjectSight API

The Trimble ProjectSight API provides portfolio and project information management for construction. Enables programmatic access to project data, submittals, RFIs, and document workflows for construction project management.

- **Human URL:** [https://developer.trimble.com/docs/projectsight](https://developer.trimble.com/docs/projectsight)

#### Tags

- Construction
- Project Management
- Documents

#### Properties

- [Documentation](https://developer.trimble.com/docs/projectsight)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TruckMate API

The TruckMate REST API provides transactional and configuration operations for Trimble's transportation management system (TMS). Enables freight brokers, carriers, and logistics operators to automate dispatch, load management, and billing workflows.

- **Human URL:** [https://developer.trimble.com/docs/truckmate](https://developer.trimble.com/docs/truckmate)

#### Tags

- Transportation
- TMS
- Logistics
- Freight

#### Properties

- [Documentation](https://developer.trimble.com/docs/truckmate)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoPilot Navigation API

The Trimble CoPilot Navigation API enables in-cab navigation integration with cloud-based services for commercial vehicle fleets. Provides route delivery, real-time traffic, and truck-specific navigation for driver mobile applications.

- **Human URL:** [https://developer.trimble.com/docs/copilot](https://developer.trimble.com/docs/copilot)

#### Tags

- Navigation
- Transportation
- Trucking
- In-Cab

#### Properties

- [Documentation](https://developer.trimble.com/docs/copilot)
- [Developer Portal](https://developer.trimblemaps.com/copilot-navigation/)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMT Fleet Maintenance API

The TMT (Trimble Maintenance Technology) REST API provides fleet maintenance management operations for commercial vehicle fleets. Enables work order management, preventive maintenance scheduling, parts inventory, and repair tracking.

- **Human URL:** [https://developer.trimble.com/docs/tmt](https://developer.trimble.com/docs/tmt)

#### Tags

- Fleet Management
- Maintenance
- Transportation

#### Properties

- [Documentation](https://developer.trimble.com/docs/tmt)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Viewpoint Construction ERP APIs

The Viewpoint suite of construction ERP APIs includes Jobpac Connect, Spectrum, and Vista. These REST and web service APIs provide accounting, HR, project management, and operations integrations for construction firms.

- **Human URL:** [https://developer.trimble.com/docs/vista](https://developer.trimble.com/docs/vista)

#### Tags

- Construction ERP
- Accounting
- HR
- Finance

#### Properties

- [Documentation](https://developer.trimble.com/docs/vista)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trimble Identity API

Trimble Identity provides OAuth 2.0 / OpenID Connect authentication and authorization for all Trimble developer applications. Enables single sign-on across the Trimble platform for web, mobile, and desktop applications.

- **Human URL:** [https://developer.trimble.com/docs/authentication](https://developer.trimble.com/docs/authentication)

#### Tags

- Authentication
- OAuth 2.0
- Identity
- Security

#### Properties

- [Documentation](https://developer.trimble.com/docs/authentication)
- [Postman Collection](collections/trimble-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/trimble-maps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-maps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trimble)
- [Website](https://www.trimble.com)
- [Developer Portal](https://www.trimble.com/en/developer/docs)
- [Getting Started](https://www.trimble.com/en/developer)
- [Authentication](https://developer.trimble.com/docs/authentication)
- [Marketplace](https://developer.trimble.com/docs/marketplace)
- [Design System](https://modus.trimble.com/)
- [Blog](https://www.trimble.com/en/news)
- [Vocabulary](vocabulary/trimble-vocabulary.yml)
- [J S O N L D Context](json-ld/trimble-context.jsonld)
- [Integrations](https://www.trimble.com/en/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
