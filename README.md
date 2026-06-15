# Isometric (isometric)

Isometric is a London- and New York-based certifier of climate solutions building an AI-native, science-led registry and verification platform for the industrial economy. Founded in 2022 by Eamon Jubbawy (Onfido), Isometric certifies durable carbon dioxide removal (CDR), superpollutant abatement, and related environmental attributes against the public Isometric Standard, a library of peer-reviewed protocols spanning biochar, enhanced weathering, mineralization, direct air capture, marine CDR, biosphere pathways (such as reforestation, mangroves, agroforestry, and improved forest management), and superpollutant abatement (HFC/ODS recovery, landfill methane, rice methane). Buyers, suppliers, and integrators interact with Isometric through three primary platforms — Certify (project design, MRV data ingestion, LCA, GHG statements, validation), Registry (issuances, credit batches, deliveries, transfers, retirements, buffer pools), and Protocols (operationalized scientific methodology) — exposed via the Registry API and the Certify (MRV) Data Ingestion API. Both APIs are versioned at /v0, share a unified two-credential model (X-Client-Secret + Bearer JWT), run on sandbox and production hosts, and are accompanied by a hosted MCP server at api.isometric.com/mcp that exposes the Isometric Standard, protocols, modules, and platform documentation to AI clients such as Claude, ChatGPT, Gemini, Cursor, Windsurf, and VS Code Copilot. Customers include Google, Microsoft, Shopify, Frontier-aligned buyers, and Anglo American, and the registry powers credit lifecycle operations for marketplaces, intermediaries, and carbon intelligence platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/isometric/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/isometric/refs/heads/main/apis.yml)

## Scope

- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Carbon Removal
- Carbon Registry
- Climate
- Climate Tech
- CDR
- MRV
- Measurement Reporting Verification
- Certification
- Superpollutants
- Biochar
- Direct Air Capture
- Enhanced Weathering
- Mineralization
- Reforestation
- Mangrove Restoration
- Agroforestry
- Methane
- HFC
- Sustainability
- ESG
- Net Zero
- LCA
- Greenhouse Gas
- Protocols
- AI
- MCP

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Isometric Registry API

The Isometric Registry API provides programmatic access to the public record of carbon removal credits certified to the Isometric Standard. Versioned at /v0, it exposes resources for suppliers, organisations, beneficiaries, transferees, projects, issuances, credit batches, orders, deliveries, transfers, retirements, refunds, and buffer pools, plus Stripe-backed checkout for self-service payments. Authentication requires both an X-Client-Secret header tied to a sandbox or production environment and a JWT bearer access token scoped to a single organisation. Pagination follows the Relay cursor specification, dates are ISO 8601 UTC, and countries use ISO 3166-1 Alpha-3. Third-party integrators including marketplaces, intermediaries, and carbon intelligence platforms can request Registry API access.

- **Human URL:** [https://docs.isometric.com/api-reference/registry/registry-introduction](https://docs.isometric.com/api-reference/registry/registry-introduction)
- **Base URL:** `https://api.isometric.com/registry/v0`

#### Tags

- Carbon Removal
- Carbon Registry
- Credits
- Issuances
- Deliveries
- Transfers
- Retirements
- MRV
- Climate

#### Properties

- [Documentation](https://docs.isometric.com/api-reference/registry/registry-introduction)
- [Documentation](https://docs.isometric.com/api-reference/registry/api-changelog)
- [Documentation](https://docs.isometric.com/user-guides/registry/key-registry-concepts)
- [Authentication](https://docs.isometric.com/api-reference/authentication)
- [OpenAPI](openapi/isometric-registry-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/isometric-registry-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isometric-registry-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://docs.isometric.com/api-reference/registry/api-changelog)

### Isometric Certify Data Ingestion API

The Isometric Certify (MRV) Data Ingestion API automates the syncing of project Measurement, Reporting, and Verification (MRV) data and GHG statement submissions into the Certify platform. Versioned at /v0 under api.isometric.com/mrv/v0, it covers projects, removals and removal templates, components and component blueprints, datapoints, attribution, feedstock types and batches, production batches, storage locations and units, measurement locations and samples, monitoring submissions and requirements, GHG statements, sources and signed upload URLs, sensors, time-series data upload submissions, and signed file uploads. Suppliers using their own field equipment, LIMS, ERP, or lab systems can stream MRV evidence directly into Isometric's verification pipeline. Same dual-header auth model as the Registry API (X-Client-Secret + Bearer JWT), with sandbox and production environments.

- **Human URL:** [https://docs.isometric.com/api-reference/certify/certify-introduction](https://docs.isometric.com/api-reference/certify/certify-introduction)
- **Base URL:** `https://api.isometric.com/mrv/v0`

#### Tags

- Carbon Removal
- MRV
- Certification
- Ingestion
- LCA
- GHG Statements
- Sensors
- Climate

#### Properties

- [Documentation](https://docs.isometric.com/api-reference/certify/certify-introduction)
- [Documentation](https://docs.isometric.com/api-reference/certify/your-first-removal)
- [Documentation](https://docs.isometric.com/api-reference/certify/api-changelog)
- [Authentication](https://docs.isometric.com/api-reference/authentication)
- [OpenAPI](openapi/isometric-certify-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/isometric-certify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isometric-certify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://docs.isometric.com/api-reference/certify/api-changelog)

### Isometric MCP Server

Isometric ships a hosted Model Context Protocol (MCP) server that makes the Isometric Standard, proprietary protocols (biochar, DAC, enhanced weathering, marine CDR, biosphere, superpollutants), protocol modules, Certify and Registry user guides, and the full API documentation queryable by MCP-compatible AI clients. Pre-approved clients include Claude (Claude.ai and Claude Desktop), ChatGPT Developer mode, Google Gemini, VS Code with Copilot, Cursor, Windsurf, and Block Goose. Other clients may connect provided they support Streamable HTTP transport, OAuth Authorization, and one of two registration mechanisms (Client ID Metadata Documents preferred, or preregistration). Sandbox and production endpoints are exposed under api.sandbox.isometric.com/mcp and api.isometric.com/mcp.

- **Human URL:** [https://docs.isometric.com/user-guides/ai/mcp-server](https://docs.isometric.com/user-guides/ai/mcp-server)
- **Base URL:** `https://api.isometric.com/mcp`

#### Tags

- MCP
- Model Context Protocol
- AI
- Agents
- Documentation
- Carbon Removal

#### Properties

- [Documentation](https://docs.isometric.com/user-guides/ai/mcp-server)
- [Model Context Protocol](https://api.isometric.com/mcp)
- [Sandbox](https://api.sandbox.isometric.com/mcp)
- [Postman Collection](collections/isometric-certify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isometric-certify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/isometric-registry-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/isometric-registry-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://isometric.com)
- [Website](https://isometric.com)
- [Registry](https://registry.isometric.com)
- [Documentation](https://docs.isometric.com)
- [Getting Started](https://docs.isometric.com/getting-started)
- [Standard](https://registry.isometric.com/standard)
- [Documentation](https://registry.isometric.com/protocols)
- [Documentation](https://docs.isometric.com/user-guides/registry/introduction)
- [Documentation](https://docs.isometric.com/user-guides/certify/introduction)
- [Documentation](https://docs.isometric.com/user-guides/certify/key-certify-concepts)
- [Documentation](https://docs.isometric.com/user-guides/registry/key-registry-concepts)
- [Documentation](https://docs.isometric.com/user-guides/ai/mcp-server)
- [Changelog](https://isometric.com/changelog)
- [Blog](https://isometric.com/writing)
- [About](https://isometric.com/about)
- [Careers](https://isometric.com/careers)
- [Contact](mailto:contact@isometric.com)
- [Press](mailto:press@isometric.com)
- [LinkedIn](https://www.linkedin.com/company/isometric-tech)
- [GitHub Organization](https://github.com/isometric)
- [Product](https://isometric.com/carbon)
- [Product](https://isometric.com/superpollutants)
- [Product](https://isometric.com/registry)
- [Product](https://isometric.com/certify)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
