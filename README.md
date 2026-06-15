# Trimble (trimble)

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
