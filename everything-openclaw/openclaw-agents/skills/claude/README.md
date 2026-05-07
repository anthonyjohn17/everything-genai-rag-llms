# Claude skills (`everything-openclaw/openclaw-agents/skills/claude/`)

> **Path:** `everything-openclaw/openclaw-agents/skills/claude/` in [`everything-genai-rag-openclaw`](https://github.com/anthonyjohn17/everything-genai-rag-openclaw).

Skills for [Claude Code](https://claude.com/claude-code) — invoked via `/skill-name` slash commands or automatic triggers based on the description.

## How to install

Copy any skill folder into `~/.claude/skills/`:

```bash
cp -r skill-name ~/.claude/skills/
```

The skill is immediately available. Invoke with `/skill-name` or let Claude trigger it automatically based on the description.

## Format

Each skill is a single Markdown file with YAML frontmatter:

```markdown
---
name: skill-name
description: When to trigger this skill
---

# Instructions

What the skill should do...
```

## Skills coming soon

This folder is a placeholder for Claude Code skills. Add yours via PR.
