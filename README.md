# Xpdite docs

This repository contains the Mintlify documentation site for Xpdite.

## What is documented here

- End-user setup and quickstart
- Core workflows such as chat, tabs, models, skills, terminal, memory, and artifacts
- Integrations including MCP and the mobile Channel Bridge
- Reference material for architecture, configuration, APIs, operations, and security

The product source of truth lives in `Xpdite/source`, `Xpdite/src`, and `Xpdite/mcp_servers`.

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the local preview from the docs root:

```bash
mint dev
```

Validate internal links before you submit changes:

```bash
mint broken-links
```

## Repository layout

- `docs.json`: Mintlify configuration and navigation
- `index.mdx`, `quickstart.mdx`, `development.mdx`: primary entry pages
- `features/`: user-facing product workflows
- `integrations/`: MCP and mobile integration guides
- `reference/`: architecture, API, security, and operations
- `Xpdite/`: app code and internal draft docs used to verify public content

## Related links

- GitHub repo: `https://github.com/KashyapTan/Xpdite`
- Releases: `https://github.com/KashyapTan/Xpdite/releases`
