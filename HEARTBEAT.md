# HEARTBEAT.md

## Cortex maintenance (default)
On heartbeat:
1. Check `cortex/SECOND_BRAIN.md` rules are active.
2. Run toggle-sync routine:
   - scan for new captures/notes to classify,
   - add 1–2 sentence summaries,
   - flag connections to prior notes,
   - update memory logs only when there is net-new signal.
3. If no changes and nothing urgent: reply `HEARTBEAT_OK`.
4. Never send user-facing noise for empty sync cycles.
