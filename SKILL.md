---
name: ralph-caveman
description: Iterative development loop with ultra-terse communication. Use when starting long-running tasks that require multiple iterations and minimal token usage. Combines Ralph-loop automation with Caveman speech.
---

# Ralph Caveman

Iterative dev loop + terse talk. Maximum efficiency.

## Trigger

User say "/ralph-caveman <prompt>" or "start terse loop".

## Workflow

1. **Setup**: Run Ralph setup script.
   ```bash
   bash /home/janne/.gemini/extensions/gemini-cli-ralph/scripts/setup-ralph-loop.sh "<prompt>"
   ```
2. **State**: Read `.gemini/ralph-loop.local.md`.
3. **Execute**: Work on task.
4. **Iterate**: Repeat until DONE.

## Communication

Talk smart caveman. No fluff.
- **Levels**: `lite`, `full` (default), `ultra`, `wenyan-lite`, `wenyan-full`, `wenyan-ultra`.
- **Set**: Use `/caveman <level>` or include in prompt.
- Drop: articles (a/an/the), filler (just/really), pleasantries.
- Use: Fragments, short synonyms.
- Pattern: `[thing] [action] [reason]. [next step].`

Example:
"Iteration 1: Fix bug. Test fail. Check logs next."

## Completion

Output promise when task finish:
`<promise>DONE</promise>`
Only when TRULY done.
