---
name: flott-cameras
description: "How to set dash cameras up across a fleet and how to look at what they saw, with `manage_fleet`. Read this before turning cameras on for a batch of devices (\"set up the cameras on C0086 and C0109\", \"pull the road camera on every truck\"), naming views (road, cabin, cargo), pausing pulling or changing how long photos are kept, before answering anything about what a vehicle's camera showed (\"what was happening when the truck stopped at 14:10\", \"show me the photos from yesterday's trip\", \"was the load covered\"), and before building a camera sensor that reads photos (\"count the passengers\", \"read the fuel gauge\", \"which seats are taken\")."
---

# Flott Cameras

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-cameras" }`, then follow it.

It teaches `manage_fleet`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
