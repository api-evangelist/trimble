# Trimble

Trimble Inc. is a global technology company providing advanced positioning, navigation, and data analytics solutions across construction, agriculture, transportation, and geospatial industries. Founded in 1978 as Trimble Navigation Limited, the company integrates GPS, laser, optical, and inertial technologies with software and services. Trimble's developer platform spans construction collaboration (Trimble Connect), commercial vehicle routing (PC*MILER, Trimble Maps), building information modeling (Tekla, SketchUp), fleet management (TruckMate, TMT, CoPilot), precision positioning (Mobile Manager), and construction ERP (Viewpoint). Publicly traded on NASDAQ as TRMB.

**URL:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml)

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Trimble Connect API

The Trimble Connect API enables integration with Trimble's cloud-based construction collaboration platform. Provides access to project data, BIM models, document management, issues (BCF Topics), and team collaboration features for construction project management. Acts as the BIM collaboration hub integrating Tekla, SketchUp, and third-party tools.

**Human URL:** [https://developer.trimble.com/docs/connect](https://developer.trimble.com/docs/connect)

#### Tags

- Construction, Collaboration, BIM, Cloud, Document Management

#### Properties

- [Documentation](https://developer.trimble.com/docs/connect)
- [OpenAPI](openapi/trimble-connect-openapi.yml)
- [SpectralRules](rules/trimble-rules.yml)
- [NaftikoCapability](capabilities/bim-collaboration.yaml)
- [JSONSchema](json-schema/trimble-project-schema.json)
- [JSONStructure](json-structure/trimble-project-structure.json)
- [JSONLDContext](json-ld/trimble-context.jsonld)

### Trimble Maps API

The Trimble Maps API (formerly ALK Technologies PC*MILER) provides interactive mapping and routing solutions optimized for commercial vehicles and transportation. Enables truck-specific routing, geocoding, map tile rendering, and turn-by-turn navigation services across North America, Europe, and global markets.

**Human URL:** [https://developer.trimble.com/docs/maps](https://developer.trimble.com/docs/maps)

#### Tags

- Mapping, Transportation, Routing, Geospatial, Commercial Vehicles

#### Properties

- [Documentation](https://developer.trimble.com/docs/maps)
- [DeveloperPortal](https://developer.trimblemaps.com/)
- [OpenAPI](openapi/trimble-maps-openapi.yml)
- [NaftikoCapability](capabilities/commercial-routing.yaml)
- [JSONSchema](json-schema/trimble-route-schema.json)
- [JSONStructure](json-structure/trimble-route-structure.json)

### Trimble PC*MILER API

PC*MILER provides commercial vehicle routing and distance calculation APIs for logistics, freight, and transportation management. Delivers mileage, routing, tolls, and fuel optimization for trucking operations across North America, Europe, and global markets.

**Human URL:** [https://developer.trimble.com/docs/pc-miler](https://developer.trimble.com/docs/pc-miler)

#### Tags

- Transportation, Routing, Logistics, Distance Calculation, Commercial Vehicles

#### Properties

- [Documentation](https://developer.trimble.com/docs/pc-miler)

### Tekla API

The Tekla API provides programmatic access to Tekla Structures, a leading Building Information Modeling (BIM) software for structural engineering and detailing. Enables custom model creation, data extraction, and workflow automation for steel, concrete, and timber construction.

**Human URL:** [https://developer.tekla.com/](https://developer.tekla.com/)

#### Tags

- BIM, Structural Engineering, Construction, Modeling

#### Properties

- [Documentation](https://developer.tekla.com/)
- [DeveloperPortal](https://developer.tekla.com/)

### SketchUp API

The SketchUp API enables extension development for Trimble SketchUp, a widely-used 3D modeling and design tool. Supports Ruby and JavaScript APIs for building custom tools, plugins, and integrations for architecture, interior design, and engineering workflows.

**Human URL:** [https://developer.sketchup.com/](https://developer.sketchup.com/)

#### Tags

- 3D Modeling, Architecture, Design, Plugins

#### Properties

- [Documentation](https://developer.sketchup.com/)

### ProjectSight API

The Trimble ProjectSight API provides portfolio and project information management for construction. Enables programmatic access to project data, submittals, RFIs, and document workflows for construction project management.

**Human URL:** [https://developer.trimble.com/docs/projectsight](https://developer.trimble.com/docs/projectsight)

#### Tags

- Construction, Project Management, Documents

#### Properties

- [Documentation](https://developer.trimble.com/docs/projectsight)

### TruckMate API

The TruckMate REST API provides transactional and configuration operations for Trimble's transportation management system (TMS). Enables freight brokers, carriers, and logistics operators to automate dispatch, load management, and billing workflows.

**Human URL:** [https://developer.trimble.com/docs/truckmate](https://developer.trimble.com/docs/truckmate)

#### Tags

- Transportation, TMS, Logistics, Freight

#### Properties

- [Documentation](https://developer.trimble.com/docs/truckmate)

### CoPilot Navigation API

The Trimble CoPilot Navigation API enables in-cab navigation integration with cloud-based services for commercial vehicle fleets. Provides route delivery, real-time traffic, and truck-specific navigation for driver mobile applications.

**Human URL:** [https://developer.trimble.com/docs/copilot](https://developer.trimble.com/docs/copilot)

#### Tags

- Navigation, Transportation, Trucking, In-Cab

#### Properties

- [Documentation](https://developer.trimble.com/docs/copilot)
- [DeveloperPortal](https://developer.trimblemaps.com/copilot-navigation/)

### TMT Fleet Maintenance API

The TMT (Trimble Maintenance Technology) REST API provides fleet maintenance management operations for commercial vehicle fleets. Enables work order management, preventive maintenance scheduling, parts inventory, and repair tracking.

**Human URL:** [https://developer.trimble.com/docs/tmt](https://developer.trimble.com/docs/tmt)

#### Tags

- Fleet Management, Maintenance, Transportation

#### Properties

- [Documentation](https://developer.trimble.com/docs/tmt)

### Viewpoint Construction ERP APIs

The Viewpoint suite of construction ERP APIs includes Jobpac Connect, Spectrum, and Vista. These REST and web service APIs provide accounting, HR, project management, and operations integrations for construction firms.

**Human URL:** [https://developer.trimble.com/docs/vista](https://developer.trimble.com/docs/vista)

#### Tags

- Construction ERP, Accounting, HR, Finance

#### Properties

- [Documentation](https://developer.trimble.com/docs/vista)

### Trimble Identity API

Trimble Identity provides OAuth 2.0 / OpenID Connect authentication and authorization for all Trimble developer applications. Enables single sign-on across the Trimble platform for web, mobile, and desktop applications.

**Human URL:** [https://developer.trimble.com/docs/authentication](https://developer.trimble.com/docs/authentication)

#### Tags

- Authentication, OAuth 2.0, Identity, Security

#### Properties

- [Documentation](https://developer.trimble.com/docs/authentication)

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Trimble Connect API](openapi/trimble-connect-openapi.yml) | BIM collaboration: projects, files, BCF topics, and team members |
| [Trimble Maps API](openapi/trimble-maps-openapi.yml) | Commercial vehicle routing, geocoding, and map tiles |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [Trimble Rules](rules/trimble-rules.yml) | Spectral ruleset enforcing Trimble API conventions (operation IDs, Title Case summaries, tag requirements) |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trimble-connect.yaml](capabilities/shared/trimble-connect.yaml) | Per-API consumed definition for Trimble Connect (13 operations) |
| [capabilities/shared/trimble-maps.yaml](capabilities/shared/trimble-maps.yaml) | Per-API consumed definition for Trimble Maps / PC*MILER (6 operations) |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [capabilities/bim-collaboration.yaml](capabilities/bim-collaboration.yaml) | BIM coordination workflow: project management, file uploads, BCF issue tracking, and team management (10 tools) |
| [capabilities/commercial-routing.yaml](capabilities/commercial-routing.yaml) | Commercial vehicle routing workflow: truck route planning, mileage, geocoding, map tiles, and timezone (6 tools) |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/trimble-project-schema.json](json-schema/trimble-project-schema.json) | JSON Schema for Trimble Connect project entities |
| [json-schema/trimble-route-schema.json](json-schema/trimble-route-schema.json) | JSON Schema for PC*MILER commercial vehicle route entities |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/trimble-project-structure.json](json-structure/trimble-project-structure.json) | Structure documentation for Trimble Connect project data |
| [json-structure/trimble-route-structure.json](json-structure/trimble-route-structure.json) | Structure documentation for PC*MILER route response data |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/trimble-context.jsonld](json-ld/trimble-context.jsonld) | JSON-LD context mapping Trimble vocabulary to schema.org, W3C GEO |

## Examples

| Example | Description |
|---|---|
| [examples/trimble-connect-list-projects-example.json](examples/trimble-connect-list-projects-example.json) | List Trimble Connect projects |
| [examples/trimble-connect-create-bcf-topic-example.json](examples/trimble-connect-create-bcf-topic-example.json) | Create a BCF clash issue in a project |
| [examples/trimble-maps-calculate-route-example.json](examples/trimble-maps-calculate-route-example.json) | Calculate a truck route between three stops |
| [examples/trimble-maps-geocode-address-example.json](examples/trimble-maps-geocode-address-example.json) | Geocode a street address to coordinates |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/trimble-vocabulary.yml](vocabulary/trimble-vocabulary.yml) | Domain vocabulary for BIM, commercial routing, fleet management, construction ERP, and Trimble developer platform concepts |

## Common Links

- **Website:** [https://www.trimble.com](https://www.trimble.com)
- **Developer Portal:** [https://www.trimble.com/en/developer/docs](https://www.trimble.com/en/developer/docs)
- **Getting Started:** [https://www.trimble.com/en/developer](https://www.trimble.com/en/developer)
- **Authentication:** [https://developer.trimble.com/docs/authentication](https://developer.trimble.com/docs/authentication)
- **Marketplace:** [https://developer.trimble.com/docs/marketplace](https://developer.trimble.com/docs/marketplace)
- **Design System:** [https://modus.trimble.com/](https://modus.trimble.com/)
- **GitHub Organization:** [https://github.com/trimble-oss](https://github.com/trimble-oss)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
