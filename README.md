# Isometric (isometric)

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
