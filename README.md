# nebflow-plugin-creator

Nebflow / Stand plugin package — standalone repository for version history.

- **Version:** 1.0.0 (tag `v1.0.0`)
- **Import commit:** `b2798a6` (11 files)
- **Import date:** 2026-10-29
- **Content source:** engine seed, `src/main/resources/seed/plugins/nebflow-plugin-creator`
  in the Stand monorepo (seed last touched by commit `8b5138640 (2026-10-28 23:32:09 +0800)`)

## Editing

This repository is the place to change the package: commit here, tag releases as
`v<plugin.json version>`, and mirror the result back into the engine seed
(`src/main/resources/seed/plugins/nebflow-plugin-creator`) so freshly installed instances receive it.

## Layout

```
plugin.json    manifest (name / version / description)
Plugin.md      package guide, injected as the agent prompt on plugin assignment
skills/        one directory per skill, each with SKILL.md
mcp.json       (optional) MCP server declarations
scripts/       (optional) helper scripts
```
