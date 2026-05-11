# FusionAL Documentation — Agent Instructions

## About this project

- Documentation site for FusionAL, built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Products documented

- **FusionAL Gateway** — self-hosted MCP governance gateway (`jrm-fusional/fusional`)
- **MCP Consulting Kit** — four production MCP servers (`jrm-fusional/mcp-consulting-kit`)
- **Christopher AI** — fully local voice AI (`jrm-fusional/christopher-ai`)

## Terminology

- Use "FusionAL" (not "Fusional", "fusional", or "fusion al")
- Use "MCP server" (not "MCP plugin" or "MCP tool server")
- Use "gateway" to refer to the FusionAL Gateway process
- Use "consulting kit" to refer to the mcp-consulting-kit repo
- Use "Christopher" to refer to the Christopher AI voice assistant
- Use "registered server" for servers in the FusionAL catalog
- Ports: gateway = 8009 (local) / 8089 (Docker); BI = 8101; API hub = 8102; content = 8103; intelligence = 8104
- Use "Streamable HTTP" (not "HTTP streaming" or "streaming HTTP") for the MCP transport
- Use "SSE" for the `/sse` Claude Desktop endpoint

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use `<Warning>` callouts for Windows-specific gotchas (BOM, backslashes, %APPDATA%)
- Use `<Note>` callouts for important non-obvious facts
- Use `<Tip>` callouts for optional improvements

## Content boundaries

- Do not document internal admin features or unreleased functionality
- Do not include personal contact info beyond what's already in the repo READMEs
- Do not document the Mintlify platform itself (refer users to mintlify.com/docs)
- Security-sensitive values (API keys, passwords) should always be placeholders in examples
