# LaraPlugins MCP Server

Connect MCP clients to the [LaraPlugins](https://laraplugins.io) directory:
validated Laravel package data, including health scores, version compatibility
and vendor trust.

- **Remote endpoint:** `https://laraplugins.io/mcp/plugins`
- **Registry name:** `io.laraplugins/mcp`
- **Package:** `@laraplugins/mcp-server`

## What it exposes

- Package health scores and verdicts
- Laravel and PHP version compatibility
- Security advisories
- Semantic search across 85,814 indexed Laravel packages

## Usage

Add the remote server to your MCP client:

```json
{
  "mcpServers": {
    "laraplugins": {
      "url": "https://laraplugins.io/mcp/plugins"
    }
  }
}
```

`index.js` in this package is an empty entry point. It exists so the package can
be published to the MCP Registry. The server itself runs at the URL above.

## Sponsor

LaraPlugins is independent: no ads, no tracking, and no vendor can pay to change
a score.

[**Sponsor LaraPlugins on GitHub Sponsors**](https://github.com/sponsors/LaraPlugins)

Sponsorships cover the servers and the API, and include a sponsor badge, higher
rate limits, semantic search and data exports, depending on the tier.

## Links

- Directory: https://laraplugins.io
- API docs: https://laraplugins.io/api-docs
- Machine-readable data: https://laraplugins.io/llms.txt

Laravel is a trademark of Taylor Otwell. LaraPlugins is an independent project.
