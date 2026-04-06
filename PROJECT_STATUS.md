# PROJECT_STATUS.md

## Current focus
Wire `code-king` to use `spider-man` as the first-hop collector for public network retrieval.

## Completed
- Verified `spider-man` agent exists in local OpenClaw agent registry.
- Verified formal CLI invocation path exists via `openclaw agent --agent spider-man`.
- Added local wrapper script: `scripts/spider_collect.sh`.
- Updated `TOOLS.md` to document the formal invocation path.

## Next steps
- Run smoke test through wrapper.
- Add parent-side sanitize/defang/summarize helper if repeated often.
- Optionally add audit helper to append JSONL records automatically.

## Notes
Current chat-tool subagent API can list/steer/kill but does not expose direct targeted spawn here, so local OpenClaw CLI is the practical formal bridge.
