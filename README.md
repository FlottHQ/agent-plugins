# Flott for coding agents

[Flott](https://flotthq.com) is where transport and logistics teams run their operations: assets, drivers, trips, movements, maintenance, gauges, safety, and the records around them. This plugin lets Cursor, Claude Code and Codex work in your Flott workspaces as you, with exactly what your role allows.

## What it adds

- **The Flott MCP server** at `https://mcp.flotthq.com/mcp`. The first time it connects you sign in to Flott and choose which workspaces it can reach. You can see and revoke the connection, and every call it made, at [mcp.flotthq.com](https://mcp.flotthq.com).
- **Skills** that tell the agent when to read Flott's guides before building something: routines, interfaces, files, and the concierge. The guides themselves are served by the MCP server, so they always match the tools.
- **Commands**:
  - `/flott-brief`: today's operations in a workspace, in a minute's read.
  - `/flott-routine`: turn something done by hand into a routine that runs on its own.
  - `/flott-interface`: build a live page over the workspace's data.

## Install

**Cursor:** install **Flott** from the plugin marketplace.

**Claude Code:**

```
/plugin marketplace add FlottHQ/agent-plugins
/plugin install flott@flott
```

**Codex:** install **Flott** from the plugin directory.

Without the plugin, you can still add the server alone: see [mcp.flotthq.com/connect](https://mcp.flotthq.com/connect).

## Examples

- "Give me a brief of today's operations in Flott"
- "Every morning at 7, send me the assets due for maintenance this week"
- "Build an interface of deliveries done per day that I can share with a customer"

## What is kept

For each call, Flott keeps the tool, the workspace and the outcome: never what you asked or what came back. What a tool writes, such as a routine, an interface or a person, is saved in your workspace like anything else in Flott.

## Privacy

[Privacy policy](https://www.flotthq.com/privacy-policy) · [Terms of service](https://www.flotthq.com/terms-of-service)
