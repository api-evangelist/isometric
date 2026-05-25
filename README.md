# isometric

Isometric — AI-native certification for durable carbon removal, superpollutant abatement, and environmental attributes. Public Isometric Standard, peer-reviewed protocols, and a transparent registry with Certify + Registry APIs and a hosted MCP server.

- Website: https://isometric.com
- Registry: https://registry.isometric.com
- Docs: https://docs.isometric.com
- GitHub: https://github.com/isometric

## APIs

- **Isometric Registry API** — public credit lifecycle (issuances, credit batches, deliveries, transfers, retirements, refunds, buffer pool, Stripe checkout). `https://api.isometric.com/registry/v0`
- **Isometric Certify Data Ingestion API** — MRV data ingestion, GHG statements, components, datapoints, feedstock, production, storage, monitoring, sensors. `https://api.isometric.com/mrv/v0`
- **Isometric MCP Server** — Standard, protocols, modules, and docs surfaced to MCP clients (Claude, ChatGPT, Gemini, Cursor, Windsurf, VS Code Copilot, Block Goose). `https://api.isometric.com/mcp`

Authentication for both REST APIs is dual-credential: an `X-Client-Secret` header tied to a sandbox or production environment plus a JWT bearer access token scoped to a single organisation.
