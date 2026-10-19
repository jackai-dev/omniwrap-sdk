# <img src="./favicon.svg" width="28" height="28" alt="OmniWrap" /> OmniWrap Official Polyglot SDKs (`v1.0.0`)

Official 8-language SDK suite and Agentic Packs for **[OmniWrap](https://omniwrap.net)**, deterministically generated and synchronized across [`jackai-dev`](https://github.com/orgs/jackai-dev).

Every language repository ships with a zero-dependency native HTTP client, typed models, pagination/streaming helpers, SHA-256 artifact provenance (`omniwrap-artifact.json`), and the full **Agentic Pack** (`SKILL.md`, `AGENTS.md`, `llms.txt`, `.mcp.json`, `mcp/server.py`).

## Dedicated SDK Repositories (8 Languages)

| Language | Dedicated Repository | OmniWrap Renderer | Install / Usage |
| :--- | :--- | :--- | :--- |
| **TypeScript** | [`jackai-dev/omniwrap-sdk-typescript`](https://github.com/jackai-dev/omniwrap-sdk-typescript) | `typescript` | `npm install @jackai-dev/omniwrap-sdk` |
| **JavaScript (ESM)** | [`jackai-dev/omniwrap-sdk-javascript`](https://github.com/jackai-dev/omniwrap-sdk-javascript) | `javascript` | `npm install @jackai-dev/omniwrap-sdk-js` |
| **Python** | [`jackai-dev/omniwrap-sdk-python`](https://github.com/jackai-dev/omniwrap-sdk-python) | `python` | `pip install omniwrap-sdk` |
| **Go** | [`jackai-dev/omniwrap-sdk-go`](https://github.com/jackai-dev/omniwrap-sdk-go) | `go` | `go get github.com/jackai-dev/omniwrap-sdk-go` |
| **Rust** | [`jackai-dev/omniwrap-sdk-rust`](https://github.com/jackai-dev/omniwrap-sdk-rust) | `rust` | `cargo add omniwrap-sdk` |
| **Java** | [`jackai-dev/omniwrap-sdk-java`](https://github.com/jackai-dev/omniwrap-sdk-java) | `java` | `implementation("dev.jackai:omniwrap-sdk:1.0.0")` |
| **.NET / C#** | [`jackai-dev/omniwrap-sdk-dotnet`](https://github.com/jackai-dev/omniwrap-sdk-dotnet) | `dotnet` | `dotnet add package JackAI.OmniWrap.Sdk` |
| **Kotlin** | [`jackai-dev/omniwrap-sdk-kotlin`](https://github.com/jackai-dev/omniwrap-sdk-kotlin) | `kotlin` | `implementation("dev.jackai:omniwrap-sdk-kotlin:1.0.0")` |

## Reproduce Locally with OmniWrap CLI

```bash
# Generate any target SDK + MCP server + Agent Skill from openapi.json
omniwrap gen --from-openapi openapi.json --mode http_client --renderer typescript --with-mcp --with-skill --out ./dist/ts
```

## License

GPL-3.0-or-later / MIT Runtime Package — Copyright (c) 2026 JackAI Technologies Inc.
