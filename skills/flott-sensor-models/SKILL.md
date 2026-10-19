---
name: flott-sensor-models
description: "How to set the same sensor up on many assets, prove it works and look after it, with `manage_sensor_models`. Read this before building a camera or telemetry sensor for more than one or two assets (\"detect which seats are taken on our 10 assets\", \"the fuel litres on every Volvo\"), when a sensor reads right on some assets and wrong on others, before labelling photos or readings to score a sensor, before deploying a sensor change to a fleet or rolling one back, and when asked to keep a model right over time."
---

# Flott Sensor Models

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-sensor-models" }`, then follow it.

It teaches `manage_sensor_models`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
