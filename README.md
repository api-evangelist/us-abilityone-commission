# US AbilityOne Commission (us-abilityone-commission)
The US AbilityOne Commission is an independent federal agency that administers the AbilityOne Program, which creates employment opportunities for individuals who are blind or have significant disabilities. Operating under the Javits-Wagner-O'Day (JWOD) Act, the Commission maintains the AbilityOne Procurement List — a catalog of products and services that federal agencies are required to purchase from qualified nonprofit agencies employing people who are blind or have significant disabilities. The PLIMS (Procurement List Information Management System) provides web-based search access to the products and services list. Two central nonprofit agencies, NIB (National Industries for the Blind) and SourceAmerica, manage the affiliated nonprofit network.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/us-abilityone-commission/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Federal Government, Disability Employment, Procurement, Nonprofit, Accessibility

## Timestamps

- **Created:** 2024-11-20
- **Modified:** 2026-05-03

## APIs

### AbilityOne Procurement List API
The Procurement List Information Management System (PLIMS) provides search access to the AbilityOne Procurement List — the catalog of products (identified by NSN) and services that federal agencies are mandated to procure from AbilityOne-participating nonprofit agencies. Supports search by NSN, product description, service type, agency, and nonprofit affiliate.

**Human URL:** [https://plims.abilityone.gov/search-products/](https://plims.abilityone.gov/search-products/)

#### Tags:

 - Procurement, Products, Services, NSN, Federal Acquisition

#### Properties

- [Documentation](https://www.abilityone.gov/procurement_list/)
- [OpenAPI](openapi/abilityone-procurement-list-api-openapi.yml)
- [JSONSchema - Product](json-schema/procurement-list-api-product-schema.json)
- [JSONSchema - Service](json-schema/procurement-list-api-service-schema.json)

## Common Properties

- [Website](https://www.abilityone.gov)
- [Portal](https://plims.abilityone.gov)
- [Documentation](https://www.abilityone.gov/procurement_list/)
- [DataAPI](https://plims.abilityone.gov/reports/)
- [JSONLD](json-ld/us-abilityone-commission-context.jsonld)
- [SpectralRules](rules/us-abilityone-commission-spectral-rules.yml)
- [Vocabulary](vocabulary/us-abilityone-commission-vocabulary.yaml)
- [NaftikoCapability - Disability Employment Procurement](capabilities/disability-employment-procurement.yaml)
- [NaftikoCapability - Procurement List API (Shared)](capabilities/shared/procurement-list-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Procurement List Search | Web-based search of the AbilityOne Procurement List by NSN, product description, agency, and nonprofit affiliate via PLIMS. |
| Products List | Searchable and downloadable catalog of products on the AbilityOne Procurement List, identified by National Stock Number (NSN). |
| Services List | Searchable catalog of services on the AbilityOne Procurement List, organized by service category and performing nonprofit agency. |
| Nonprofit Agency Directory | Directory of NIB-affiliated and SourceAmerica-affiliated nonprofit agencies that employ people who are blind or have significant disabilities. |
| Reports and Data Downloads | Downloadable Excel reports of the Procurement List products and services, nonprofit agency rosters, and distributor lists. |

## Use Cases

| Name | Description |
|------|-------------|
| Federal Acquisition Compliance | Federal contracting officers verifying mandatory source requirements for AbilityOne products and services before placing orders. |
| Procurement List Lookup | Defense and civilian agencies searching by NSN to determine if a product must be procured through the AbilityOne program. |
| Nonprofit Agency Discovery | Federal buyers identifying which nonprofit agency supplies a specific product or service in their geographic region. |
| Distributor Integration | Authorized distributors accessing the Procurement List to maintain current product catalogs and pricing. |

## Integrations

| Name | Description |
|------|-------------|
| NIB (National Industries for the Blind) | Central nonprofit agency managing blind-employing organizations participating in the AbilityOne program. |
| SourceAmerica | Central nonprofit agency managing organizations employing people with significant disabilities in the AbilityOne program. |
| GSA Advantage | GSA procurement platform where AbilityOne products are listed and available for federal purchase. |
| SAM.gov | System for Award Management integration for federal contract and acquisition data linked to AbilityOne awards. |
| FPDS | Federal Procurement Data System tracking AbilityOne program spending and contract awards across federal agencies. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AbilityOne Procurement List API](openapi/abilityone-procurement-list-api-openapi.yml)

### JSON Schema

- [Product](json-schema/procurement-list-api-product-schema.json)
- [Service](json-schema/procurement-list-api-service-schema.json)
- [Agency](json-schema/procurement-list-api-agency-schema.json)
- [Product Search Response](json-schema/procurement-list-api-product-search-response-schema.json)
- [Service Search Response](json-schema/procurement-list-api-service-search-response-schema.json)
- [Agency List Response](json-schema/procurement-list-api-agency-list-response-schema.json)
- *(7 total schema files in json-schema/)*

### JSON Structure

- *(7 total structure files in json-structure/)*

### JSON-LD

- [US AbilityOne Commission Context](json-ld/us-abilityone-commission-context.jsonld)

### Examples

- [Product Example](examples/procurement-list-api-product-example.json)
- [Service Example](examples/procurement-list-api-service-example.json)
- [Agency Example](examples/procurement-list-api-agency-example.json)
- *(7 total example files in examples/)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Procurement List API](capabilities/shared/procurement-list-api.yaml) — 6 operations for product search, service search, agency directory, and report downloads

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Disability Employment Procurement](capabilities/disability-employment-procurement.yaml) | Procurement List API | 6 | Contracting Officer, Procurement Specialist, Agency Procurement Manager |

## Vocabulary

- [US AbilityOne Commission Vocabulary](vocabulary/us-abilityone-commission-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 4 actions, 1 workflow, and 3 personas across operational and capability dimensions

## Rules

- [US AbilityOne Commission Spectral Rules](rules/us-abilityone-commission-spectral-rules.yml) — Rules across multiple categories enforcing AbilityOne API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
