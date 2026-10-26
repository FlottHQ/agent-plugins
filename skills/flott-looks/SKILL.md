---
name: flott-looks
description: "How to give a fleet's assets and sites their look on the map with `manage_looks`. Read this before drawing a vehicle's top view (\"make the HOWO tippers look like HOWOs on the map\", \"draw our white Toyota pickups\"), starting one from a model in a company's colours (\"our trucks are red and white\"), changing a look's colours or giving a fleet its own (\"the Bouaké fleet in green\", \"a darker blue\"), choosing which assets wear a look (\"all trucks in Abidjan wear the tipper\"), marking a site's parts (gate, weighbridge, parking, loading bays) or drawing and showing its plan (\"show the terminal's plan on the map\", \"add the four loading bays\"), and before answering how a site's day went (\"how long did trucks wait at the weighbridge yesterday\")."
---

# Flott Looks

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-looks" }`, then follow it.

It teaches `manage_looks`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
