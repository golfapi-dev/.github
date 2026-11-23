<img src="birdie.png" alt="Birdie, the GolfAPI.dev mascot" width="64" align="right" />

# GolfAPI.dev

Golf club specifications as each maker published them: lofts, lies, head volume, hands, adjustable hosels, release dates and US launch prices for 2,700+ club models released 2000 to 2026, from drivers to putters. Read them through a REST API or an MCP server in your AI assistant.

## Try it

MCP server, for Claude, ChatGPT, Cursor, VS Code and other MCP clients:

```
https://mcp.golfapi.dev
```

REST API, with a free key from [console.golfapi.dev](https://console.golfapi.dev/?plan=free&ref=github):

```sh
curl https://api.golfapi.dev/drivers?release_year=2025 \
  -H "Authorization: Bearer $GOLFDEV_API_KEY"
```

## Repositories

| Repository | What it holds |
| --- | --- |
| [mcp](https://github.com/golfapi-dev/mcp) | The MCP plugin package and setup for each AI client |
| [examples](https://github.com/golfapi-dev/examples) | Small scripts in Python, JavaScript and curl that call the API |
| [openapi](https://github.com/golfapi-dev/openapi) | The OpenAPI document for the REST API |

## Links

[Docs](https://golfapi.dev/docs/?ref=github) · [MCP setup](https://golfapi.dev/mcp?ref=github) · [Pricing](https://golfapi.dev/pricing/?ref=github) · [Status](https://golfapi.dev/status/?ref=github) · hello@golfapi.dev
