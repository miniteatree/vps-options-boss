# ARCHITECTURE_NOTES.md

## Network retrieval delegation pattern

For public network retrieval, `code-king` should not fetch directly when `spider-man` is available.

### Formal call path

`code-king` -> `scripts/spider_collect.sh` -> `openclaw agent --agent spider-man --json --message ...` -> `spider-man` returns collector JSON -> `code-king` sanitizes/defangs/summarizes.

### Why this path

- The chat runtime tool surface here does not expose a direct targeted spawn API for an already-defined agent.
- The local OpenClaw CLI *does* expose a formal targeted invocation path via `openclaw agent --agent <id>`.
- This keeps the delegation explicit, reproducible, and aligned with the existing local agent registry.

### Collector contract

Expected raw output from `spider-man`:

```json
{
  "task_id": "...",
  "sources": [{"url": "...", "fetched_at": "..."}],
  "raw_payload": [{"url": "...", "content": "..."}],
  "collector_risk_flags": []
}
```

### Current limitation

In the current runtime, `spider-man` has minimal tools available and may return `fetch_unavailable` if external fetch is not exposed in its runtime.

### Next improvement

If repeated often, add a parent-side helper to:
- parse collector JSON
- sanitize secrets/patterns
- defang instruction-like text
- append one audit line to `memory/spider-man-audit.jsonl`
- emit user-facing summary JSON
