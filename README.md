# Isometric

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

**Areas:** Carbon Removal · Carbon Registry · Climate · Climate Tech · CDR · MRV · Measurement Reporting Verification · Certification · Superpollutants · Biochar · Direct Air Capture · Enhanced Weathering

## Isometric on APIs.io

Everything profiled for Isometric is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/isometric/](https://apis.io/providers/isometric/)** — or go straight to one of the APIs or properties below.

### APIs (36)

- [Isometric MCP Server](https://apis.io/apis/isometric/isometric-mcp-server/) — Isometric ships a hosted Model Context Protocol (MCP) server that makes the Isometric Standard, proprietary protocols (biochar, DAC, enhanced weathering,…
- [Isometric Beneficiaries API](https://apis.io/apis/isometric/isometric-beneficiaries-api/) — The Beneficiaries API from Isometric — 1 operation(s) for beneficiaries.
- [Isometric Beneficiary API](https://apis.io/apis/isometric/isometric-beneficiary-api/) — The Beneficiary API from Isometric — 1 operation(s) for beneficiary.
- [Isometric Biochar Applications API](https://apis.io/apis/isometric/isometric-biochar-applications-api/) — The Biochar Applications API from Isometric — 2 operation(s) for biochar applications.
- [Isometric Component Blueprints API](https://apis.io/apis/isometric/isometric-component-blueprints-api/) — The Component Blueprints API from Isometric — 2 operation(s) for component blueprints.
- [Isometric Components API](https://apis.io/apis/isometric/isometric-components-api/) — The Components API from Isometric — 2 operation(s) for components.
- [Isometric Credit Batches API](https://apis.io/apis/isometric/isometric-credit-batches-api/) — The Credit Batches API from Isometric — 1 operation(s) for credit batches.
- [Isometric Data Upload Submissions API](https://apis.io/apis/isometric/isometric-data-upload-submissions-api/) — The Data Upload Submissions API from Isometric — 2 operation(s) for data upload submissions.
- [Isometric Datapoints API](https://apis.io/apis/isometric/isometric-datapoints-api/) — The Datapoints API from Isometric — 4 operation(s) for datapoints.
- [Isometric Deliveries API](https://apis.io/apis/isometric/isometric-deliveries-api/) — The Deliveries API from Isometric — 3 operation(s) for deliveries.
- [Isometric Feedstock Batches API](https://apis.io/apis/isometric/isometric-feedstock-batches-api/) — The Feedstock Batches API from Isometric — 2 operation(s) for feedstock batches.
- [Isometric Feedstock Types API](https://apis.io/apis/isometric/isometric-feedstock-types-api/) — The Feedstock Types API from Isometric — 3 operation(s) for feedstock types.
- [Isometric File Uploads API](https://apis.io/apis/isometric/isometric-file-uploads-api/) — The File Uploads API from Isometric — 1 operation(s) for file uploads.
- [Isometric Ghg Statement Components API](https://apis.io/apis/isometric/isometric-ghg-statement-components-api/) — The Ghg Statement Components API from Isometric — 1 operation(s) for ghg statement components.
- [Isometric Ghg Statements API](https://apis.io/apis/isometric/isometric-ghg-statements-api/) — The Ghg Statements API from Isometric — 3 operation(s) for ghg statements.
- [Isometric Issuances API](https://apis.io/apis/isometric/isometric-issuances-api/) — The Issuances API from Isometric — 3 operation(s) for issuances.
- [Isometric Measurement Locations API](https://apis.io/apis/isometric/isometric-measurement-locations-api/) — The Measurement Locations API from Isometric — 2 operation(s) for measurement locations.
- [Isometric Measurement Samples API](https://apis.io/apis/isometric/isometric-measurement-samples-api/) — The Measurement Samples API from Isometric — 1 operation(s) for measurement samples.
- [Isometric Orders API](https://apis.io/apis/isometric/isometric-orders-api/) — The Orders API from Isometric — 2 operation(s) for orders.
- [Isometric Organisation API](https://apis.io/apis/isometric/isometric-organisation-api/) — The Organisation API from Isometric — 1 operation(s) for organisation.
- [Isometric Organisations API](https://apis.io/apis/isometric/isometric-organisations-api/) — The Organisations API from Isometric — 4 operation(s) for organisations.
- [Isometric Processes API](https://apis.io/apis/isometric/isometric-processes-api/) — The Processes API from Isometric — 1 operation(s) for processes.
- [Isometric Production Batches API](https://apis.io/apis/isometric/isometric-production-batches-api/) — The Production Batches API from Isometric — 2 operation(s) for production batches.
- [Isometric Project Components API](https://apis.io/apis/isometric/isometric-project-components-api/) — The Project Components API from Isometric — 3 operation(s) for project components.
- [Isometric Projects API](https://apis.io/apis/isometric/isometric-projects-api/) — The Projects API from Isometric — 12 operation(s) for projects.
- [Isometric Refunds API](https://apis.io/apis/isometric/isometric-refunds-api/) — The Refunds API from Isometric — 2 operation(s) for refunds.
- [Isometric Removals API](https://apis.io/apis/isometric/isometric-removals-api/) — The Removals API from Isometric — 3 operation(s) for removals.
- [Isometric Retirements API](https://apis.io/apis/isometric/isometric-retirements-api/) — The Retirements API from Isometric — 4 operation(s) for retirements.
- [Isometric Sensors API](https://apis.io/apis/isometric/isometric-sensors-api/) — The Sensors API from Isometric — 2 operation(s) for sensors.
- [Isometric Sources API](https://apis.io/apis/isometric/isometric-sources-api/) — The Sources API from Isometric — 4 operation(s) for sources.
- [Isometric Storage Units API](https://apis.io/apis/isometric/isometric-storage-units-api/) — The Storage Units API from Isometric — 2 operation(s) for storage units.
- [Isometric Stripe API](https://apis.io/apis/isometric/isometric-stripe-api/) — The Stripe API from Isometric — 2 operation(s) for stripe.
- [Isometric Supplier API](https://apis.io/apis/isometric/isometric-supplier-api/) — The Supplier API from Isometric — 1 operation(s) for supplier.
- [Isometric Suppliers API](https://apis.io/apis/isometric/isometric-suppliers-api/) — The Suppliers API from Isometric — 6 operation(s) for suppliers.
- [Isometric Transferees API](https://apis.io/apis/isometric/isometric-transferees-api/) — The Transferees API from Isometric — 1 operation(s) for transferees.
- [Isometric Transfers API](https://apis.io/apis/isometric/isometric-transfers-api/) — The Transfers API from Isometric — 3 operation(s) for transfers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [isometric](https://apis.io/servers/isometric/isometric/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Isometric Agentic Access](https://apis.io/agentic-access/isometric/isometric-agentic-access/)

#### Collections (37)

Postman and Open Collection request collections.

- [Isometric Certify Data Ingestion Beneficiaries API](https://apis.io/collections/isometric/open-isometric-beneficiaries-api/)
- [Isometric Certify Data Ingestion Beneficiaries Beneficiary API](https://apis.io/collections/isometric/open-isometric-beneficiary-api/)
- [Isometric Certify Data Ingestion Beneficiaries Biochar Applications API](https://apis.io/collections/isometric/open-isometric-biochar-applications-api/)
- [Isometric Certify Data Ingestion API](https://apis.io/collections/isometric/open-isometric-certify-api/)
- [Isometric Certify Data Ingestion Beneficiaries Component Blueprints API](https://apis.io/collections/isometric/open-isometric-component-blueprints-api/)
- [Isometric Certify Data Ingestion Beneficiaries Components API](https://apis.io/collections/isometric/open-isometric-components-api/)
- [Isometric Certify Data Ingestion Beneficiaries Credit Batches API](https://apis.io/collections/isometric/open-isometric-credit-batches-api/)
- [Isometric Certify Data Ingestion Beneficiaries Data Upload Submissions API](https://apis.io/collections/isometric/open-isometric-data-upload-submissions-api/)
- [Isometric Certify Data Ingestion Beneficiaries Datapoints API](https://apis.io/collections/isometric/open-isometric-datapoints-api/)
- [Isometric Certify Data Ingestion Beneficiaries Deliveries API](https://apis.io/collections/isometric/open-isometric-deliveries-api/)
- [Isometric Certify Data Ingestion Beneficiaries Feedstock Batches API](https://apis.io/collections/isometric/open-isometric-feedstock-batches-api/)
- [Isometric Certify Data Ingestion Beneficiaries Feedstock Types API](https://apis.io/collections/isometric/open-isometric-feedstock-types-api/)
- [Isometric Certify Data Ingestion Beneficiaries File Uploads API](https://apis.io/collections/isometric/open-isometric-file-uploads-api/)
- [Isometric Certify Data Ingestion Beneficiaries Ghg Statement Components API](https://apis.io/collections/isometric/open-isometric-ghg-statement-components-api/)
- [Isometric Certify Data Ingestion Beneficiaries Ghg Statements API](https://apis.io/collections/isometric/open-isometric-ghg-statements-api/)
- [Isometric Certify Data Ingestion Beneficiaries Issuances API](https://apis.io/collections/isometric/open-isometric-issuances-api/)
- [Isometric Certify Data Ingestion Beneficiaries Measurement Locations API](https://apis.io/collections/isometric/open-isometric-measurement-locations-api/)
- [Isometric Certify Data Ingestion Beneficiaries Measurement Samples API](https://apis.io/collections/isometric/open-isometric-measurement-samples-api/)
- [Isometric Certify Data Ingestion Beneficiaries Orders API](https://apis.io/collections/isometric/open-isometric-orders-api/)
- [Isometric Certify Data Ingestion Beneficiaries Organisation API](https://apis.io/collections/isometric/open-isometric-organisation-api/)
- [Isometric Certify Data Ingestion Beneficiaries Organisations API](https://apis.io/collections/isometric/open-isometric-organisations-api/)
- [Isometric Certify Data Ingestion Beneficiaries Processes API](https://apis.io/collections/isometric/open-isometric-processes-api/)
- [Isometric Certify Data Ingestion Beneficiaries Production Batches API](https://apis.io/collections/isometric/open-isometric-production-batches-api/)
- [Isometric Certify Data Ingestion Beneficiaries Project Components API](https://apis.io/collections/isometric/open-isometric-project-components-api/)
- [Isometric Certify Data Ingestion Beneficiaries Projects API](https://apis.io/collections/isometric/open-isometric-projects-api/)
- …and 12 more published on APIs.io

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Isometric Authentication](https://apis.io/security/isometric/isometric-authentication/)
- [Isometric Domain Security](https://apis.io/security/isometric/isometric-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://isometric.com)
- [Documentation](https://docs.isometric.com)
- [Getting started](https://docs.isometric.com/getting-started)
- [Changelog](https://isometric.com/changelog)
- [Blog](https://isometric.com/writing)
- [GitHub](https://github.com/isometric)

## API Evangelist rating

**Kin Score 30.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 51.0 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 48.8 |
| Access clarity | 0.0 |

**Agent readiness 46.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 8.9** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/isometric/](https://apis.io/providers/isometric/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Isometric: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/isometric/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
