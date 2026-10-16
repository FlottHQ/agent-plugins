---
description: Turn something done by hand into a Flott routine that runs on its own — on a schedule, on an event, or when a customer asks.
argument-hint: what should happen, and when
---

# New routine

The person wants: $ARGUMENTS

1. Use the Flott MCP server. If its tools are not available, ask the person to connect it (https://mcp.flotthq.com/connect) and stop.
2. Read the guide first: call `use_skills` with `{ "action": "read", "skill": "flott-routines" }`, and follow it over anything below.
3. If the workspace, what starts the routine, or what it should produce is unclear, ask — one question at a time, and only what the guide says you need.
4. Build it with `manage_routines` as the guide describes, and test it before anything else.
5. Show the person what it will do and what the test returned. Publish only once they say so.
