# claude-starter-pack

My Claude Code plugin with the skills and MCP servers I use in every project.

## What it has

| Skill | Source |
| --- | --- |
| grill-me, grilling | mattpocock/skills |
| find-skills | vercel-labs/skills |
| frontend-design | anthropics/skills |
| systematic-debugging | obra/superpowers |
| context7-mcp | upstash/context7 |

MCP: Context7 (`https://mcp.context7.com/mcp`, OAuth on first use).

## Install in a project

```
/plugin marketplace add Juanca632/claude-starter-pack
/plugin install starter-pack@juanca632
```

Choose the **project** scope so it is saved in the repo's `.claude/settings.json`.

## Update

Edit the files here, bump `version` in `plugins/starter-pack/.claude-plugin/plugin.json`, push, then run `/plugin marketplace update juanca632` in the projects.
