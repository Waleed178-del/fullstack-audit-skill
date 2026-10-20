# fullstack-audit

A Claude Code skill that orchestrates 30 read-only specialist agents to audit a codebase across backend, frontend, UI/UX, functionality, and architecture, then produces one ranked report.

## Install
```
git clone https://github.com/Waleed178-del/fullstack-audit-skill /tmp/fas && cp -r /tmp/fas/skills/fullstack-audit ~/.claude/skills/
```
Start a new Claude Code session and say "run fullstack-audit".

See `SKILL.md` for the protocol and `agents/` for the 30 agent briefs.
