---
name: flott-asset-models
description: "How to build what an installation is made of with `manage_asset_models` — a production line, a cold room, a pumping station, a generator set — and wire it to the devices on each asset built that way. Read this before drawing a plant's line from a P&ID, a photo, a list of equipment or a description (\"model our yoghurt line\", \"add the second pasteuriser\", \"the CIP loop goes back to the tank\"), before drawing how it looks on the asset's page as a live SVG (\"draw the plant from the front\", \"the silo should fill as it weighs\", a truck from above), before giving a model to assets (\"lines 2 and 3 are built the same\"), and before binding points to a device's values or controls (\"the level is ain1\", \"start the pump from the app\")."
---

# Flott Asset models

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-asset-models" }`, then follow it.

It teaches `manage_asset_models`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
