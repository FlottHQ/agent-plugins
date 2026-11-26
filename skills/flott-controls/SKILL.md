---
name: flott-controls
description: "How to send things to devices, hold them in a state, and set up what can be sent, with `manage_controls`. Read this before adding a button to a device (\"add a control to open the gate\", \"a siren on truck 12\", \"let dispatch message the phones\"), before holding one (\"keep the trucks locked at night\", \"run the oven at 180 for 40 minutes then 120 for 20\"), before sending one (\"open the tipper on HOWO 4\", \"sound the siren on every truck at the depot\", \"ask the tracker where it is\", \"take a photo with Awa's phone\"), when somebody asks whether a send went through or why it did not, and when one waits for approval."
---

# Flott Controls

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-controls" }`, then follow it.

It teaches `manage_controls`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
