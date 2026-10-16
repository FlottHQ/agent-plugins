---
name: flott-artifact-design
description: "The Flott design system for building HTML artifacts — one self-contained document rendered in a sandboxed iframe (Geist typography, light theme, tonal surfaces). An artifact can be any document, and this covers the HTML kind: read it whenever you create or edit an artifact whose body is markup (`manage_artifacts` with `html`, or a `product.artifact` html record) for the exact color, typography, spacing and component tokens plus the rendering contract. An artifact is a STATIC SNAPSHOT: every figure is baked in when you build it and nothing is fetched when it is opened, so it suits a one-off analysis of a moment that has passed and not anything somebody reopens expecting current data. If the thing being asked for has to stay true over time — a tracker, a dashboard somebody checks weekly, a page a customer or a colleague opens whenever they like — that is a DASHBOARD: stop and read flott-dashboards instead."
---

# Flott Artifact Design System

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-artifact-design" }`, then follow it.

It teaches `manage_artifacts`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
