---
name: flott-dashboards
description: "How to build a Flott DASHBOARD with the `manage_dashboards` tool — a LIVE web page at its own address on the org's domain that re-reads the org's data every time it is opened. It is a program in JSX with Tailwind, run in the reader's browser, reading data through its own FUNCTIONS. Read this whenever what is wanted has to stay current rather than freeze: \"track the deliveries done per day\", \"somewhere I can watch the fuel spend\", \"let the customer see where their trucks are\", \"a link I can send them\". Also for any dashboard, chart, map, tracker or summary page over a table, a 3D view of a site drawn from the data (\"show the yard in 3D\"), a page its reader can act on (\"a button that reruns the forecast\"), and whenever you are writing a dashboard's document. The reader is as often a colleague as an outsider. A one-off write-up of a moment that has passed is an artifact (manage_artifacts) instead. Scheduled work is a routine: see flott-routines."
---

# Flott Dashboards

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-dashboards" }`, then follow it.

It teaches `manage_dashboards`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
