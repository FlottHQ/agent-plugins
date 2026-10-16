---
description: Build a live Flott dashboard — a page on the workspace's domain that re-reads its data every time it is opened.
argument-hint: what it should show, and who reads it
---

# New dashboard

The person wants: $ARGUMENTS

1. Use the Flott MCP server. If its tools are not available, ask the person to connect it (https://mcp.flotthq.com/connect) and stop.
2. Read the guide first: call `use_skills` with `{ "action": "read", "skill": "flott-dashboards" }`, and follow it over anything below. If what they describe is a one-off write-up of a moment that has passed, the guide will send you to `flott-artifact-design` instead.
3. If the workspace, the reader (a colleague or someone outside the company) or the figures that matter are unclear, ask before building.
4. Build it with `manage_dashboards` as the guide describes, preview it, and fix what the preview shows.
5. Give the person its address and say who can open it. Publish only once they say so.
