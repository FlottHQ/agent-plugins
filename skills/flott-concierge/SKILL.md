---
name: flott-concierge
description: "How to shape the Flott CONCIERGE — the agent that holds conversations with people OUTSIDE the company (a customer's dispatchers, your drivers, one supplier) wherever they write from — with `manage_users` for who they are and what may be done for them, and `manage_channels` for the addresses they arrive on. Read this whenever somebody says what the agent should do, know, or sound like for somebody in particular (\"Acme should be able to check their own deliveries\", \"it keeps offering things we don't do\", \"make it more formal with this client\", \"let our drivers start the daily report\", \"why is it not answering\"), and whenever you are asked to set up an agent for customers, drivers or suppliers."
---

# Flott Concierge

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-concierge" }`, then follow it.

It teaches `manage_users` and `manage_channels`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
