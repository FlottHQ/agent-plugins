---
name: flott-access
description: "Who may start a locked vehicle, with `manage_access`. Read this before putting a lock on a vehicle or arming one (\"lock the Corolla\", \"only Moussa may drive AB-123\"), before holding or releasing somebody (\"block drivers with a negative balance\", \"the car was stolen, stop it\", \"let Awa drive again\"), when somebody asks why a car will not start, and before building a routine that holds people."
---

# Flott Access

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-access" }`, then follow it.

It teaches `manage_access`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
