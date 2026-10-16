---
name: flott-routines
description: "How to make a Flott ROUTINE — the only thing in Flott that runs on its own — with the single `manage_routines` tool: choosing between a routine that needs no judgment, one that prepares data and then judges it, and one that is only a prompt; building its graph; wiring what starts it; declaring the inputs it needs so the agent on a channel can start it for a customer; testing and publishing it. Read this whenever the user wants to reuse or repeat something (\"save this so I can run it anytime\", \"every morning…\", \"whenever X happens…\", \"when a customer asks…\", \"when we tag the agent in the group\"), or whenever you are wiring a routine's steps."
---

# Flott Routines

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-routines" }`, then follow it.

It teaches `manage_routines`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
