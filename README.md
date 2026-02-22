# Flowra documentation

Documentation for the [Flowra](https://flowra.dev) API — build agents, workflows, and integrations. Built with [Mintlify](https://mintlify.com).

## Contents

- **Guides** — Getting started, authentication, API keys, and guides for tools, auth configs, triggers, connected accounts, and MCP.
- **API reference** — Generated from `api-reference/openapi.json` (Flowra API Key endpoints).

## Local preview

```bash
npm i -g mint
mint dev
```

Open **http://localhost:3000**.

## Check links

```bash
mint broken-links
```

## Project structure

- `docs.json` — Site config and navigation.
- `index.mdx`, `quickstart.mdx`, `authentication.mdx`, `api-keys.mdx` — Getting started.
- `guides/*.mdx` — Tools, auth configs, triggers, connected accounts, MCP.
- `api-reference/openapi.json` — OpenAPI spec for the API reference tab.
- `development.mdx` — Contributing to the docs site.
