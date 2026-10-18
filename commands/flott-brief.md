---
description: A short brief of today's operations in a Flott workspace — what is moving, what is late, what needs attention.
---

# Today's operations

Write a brief someone could read in a minute before their day starts. Read only: change nothing.

1. Use the Flott MCP server. If its tools are not available, ask the person to connect it (https://mcp.flotthq.com/connect) and stop.
2. If they reach more than one workspace and did not say which, ask which one.
3. Start with `query_entities` (`action: "describe"`) to see what this workspace tracks, then call each product tool you need with `action: "describe"` before its first real call. Do not guess parameters.
4. Gather, for today:
   - trips: planned, in progress, done, and any over their type's limits or waiting for review (`manage_trips`);
   - assets off the road or due for maintenance (`manage_fleet`, `manage_maintenance`);
   - open safety events, if the workspace has them (`manage_safety`);
   - anything else the describe calls show is overdue or waiting on somebody.
5. Answer in the person's language, in this order: what needs a decision now, then what is at risk today, then a few figures for the day. Name assets, drivers and customers as the workspace names them. Leave out any section with nothing in it rather than writing "none".
