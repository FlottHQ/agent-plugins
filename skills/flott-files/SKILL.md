---
name: flott-files
description: "How to work everything the org KEEPS with the single `manage_files` tool — reading a file somebody put there, storing one you produced so it is still there next month, and creating a table for a kind of record that does not exist yet. Read this whenever the thing in question is a file (\"send me the report\", \"here is the invoice, file it\", \"what does this spreadsheet say\", \"where did we put the insurance certificate\", \"we need somewhere to keep our suppliers\"), and read it before you decide whether something becomes a document or a table of records, because that choice is easy to get quietly wrong. Containers are called SPACES and live in the Files section, never \"buckets\", however the parameters are spelled. NOT for attaching a file to a message — that is `reply`."
---

# Flott Files

The full guide is served by the Flott MCP server, so it always matches the tools you are about to call. Read it before doing this work:

Call the Flott server's `use_skills` tool with `{ "action": "read", "skill": "flott-files" }`, then follow it.

It teaches `manage_files`. If `use_skills` is not available, the Flott MCP server is not connected yet: ask the person to connect it (it signs them in to Flott the first time), or to follow https://mcp.flotthq.com/connect.
