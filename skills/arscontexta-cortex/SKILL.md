---
name: arscontexta-cortex
description: OpenClaw-native alias skill for Ars Contexta workflows, mapped to the local Cortex knowledge base. Use when user asks for Ars Contexta setup, context architecture, vault structure, or second-brain operations.
metadata: {"clawdbot":{"emoji":"🧠","always":true}}
---

# ArsContexta ↔ Cortex Alias

This skill bridges Ars Contexta concepts into this OpenClaw workspace.

## Canonical locations
- Cortex root: `/Users/liamellis/.openclaw/workspace/cortex`
- Second-brain policy: `/Users/liamellis/.openclaw/workspace/cortex/SECOND_BRAIN.md`
- Ars Contexta source repo: `/Users/liamellis/.openclaw/workspace/arscontexta`
- Ars Contexta reference: `/Users/liamellis/.openclaw/workspace/arscontexta/README.md`

## Alias behavior
When user asks for Ars Contexta setup/usage in OpenClaw:
1. Treat `cortex/` as the vault root (replaces old `brain/` naming).
2. Follow `cortex/SECOND_BRAIN.md` for capture/categorize/summarize/connect/surface behavior.
3. Use Cortex context packs via: `Use cortex: <context-id>`.
4. Keep heartbeat/toggle-sync maintenance aligned with `HEARTBEAT.md`.

## Setup intent mapping
- `/arscontexta:setup` intent in this environment means:
  - verify Cortex structure,
  - verify SECOND_BRAIN policy,
  - verify heartbeat maintenance loop,
  - then apply/adjust folder+process conventions in `cortex/`.

## Output style
- Brief by default.
- Prefer concrete next actions and file paths.
