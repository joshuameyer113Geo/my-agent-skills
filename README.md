# My Agent Skills

Hand-picked skills for AI agents. Each skill is a folder containing a `SKILL.md` file that teaches an agent a new ability on demand.

## Skills

| Skill | What it does |
|---|---|
| **docx** | Create, read, edit, and analyze Word documents (.docx). Handles tables, tracked changes, comments, templates, and PDF verification. |
| **frontend-design** | Build distinctive, non-templated web UI. Covers palette, typography, layout, motion, and copywriting with a bias toward deliberate aesthetic risk. |
| **mcp-builder** | Design and build Model Context Protocol (MCP) servers in TypeScript or Python, with tool schemas, error handling, and evaluation suites. |

## How to use

Point your agent at any `skills/` subdirectory. The `SKILL.md` frontmatter (`name` + `description`) is what the agent reads to decide when to load the full instructions.

## Source

All three skills are from Anthropic's official [skills](https://github.com/anthropics/skills) repository.
