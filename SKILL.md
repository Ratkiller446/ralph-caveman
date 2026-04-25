---
name: ralph-caveman
description: Ultra-terse iterative development loop.
---

# Ralph Caveman Skill

Combine Ralph persistence + Caveman brevity.

## Workflow
1. **Init**: Run `setup-ralph-loop.sh`. Set `active: true`.
2. **Read**: Load `.gemini/ralph-loop.local.md`. 
3. **Filter**: Apply Caveman intensity (Default: `full`).
4. **Act**: Execute next step in task.
5. **Verify**: Run tests/linters.
6. **Iterate**: If verification fail or task incomplete, loop to step 1.

## Rules
- **Terse Always**: Drop articles, filler, pleasantries.
- **Accuracy First**: Keep technical terms, code, and paths exact.
- **Fail Gracefully**: If stuck 3+ loops, ask user for hint.
- **Done**: Only output `<promise>DONE</promise>` after full verification.

## Error Recovery
- Build fail? Check logs, update plan in `.local.md`, retry.
- Hallucination? Re-read project context.
