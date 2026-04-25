# 🦴 Ralph Caveman

> **Ralph loop + Caveman talk.** Build big things, use small tokens.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/Ratkiller446/ralph-caveman)

---

## 🦖 Lore: The Myth of Efficiency

Long ago, agents talk much. Many tokens. Much cost. Very slow.
Then came **Ralph**. He iterate. He never stop.
Then came **Caveman**. He drop fluff. He speak true.
Together? **Ralph Caveman**.

> "I iterate, therefore I am terse." — *Ralph the Caveman*

## 🛠️ Features

- **Persistent Iteration**: Ralph loop logic. No stop until DONE.
- **75% Token Savings**: Caveman speak. Drop "the", "a", "just".
- **Superpowers Ready**: Use with Brainstorming, Plans, Debugging.

## 🗣️ Speak Levels

| Level | Change | Example |
| :--- | :--- | :--- |
| `lite` | No filler. Pro but tight. | "Component re-renders due to new ref. Use `useMemo`." |
| `full` | Drop articles. Classic. | "New ref → re-render. Wrap in `useMemo`." |
| `ultra` | Abbrev everything. Max. | "New ref → re-render. `useMemo`." |
| `wenyan` | Classical Chinese style. | "物出新參照，致重繪。useMemo 包之。" |

## 🚀 Setup

1. **Get Gemini CLI**: Ensure latest version.
2. **Install Skill**:
   ```bash
   mkdir -p ~/.gemini/skills/ralph-caveman
   cp SKILL.md ~/.gemini/skills/ralph-caveman/
   ```

## ⌨️ Commands

| Command | Action |
| :--- | :--- |
| `/ralph-caveman "<prompt>"` | Start iterative terse loop. |
| `/caveman <level>` | Switch intensity (lite, full, ultra). |
| `stop caveman` | Return to verbose talk. |

## 🔄 Loop Flow

```text
[ USER PROMPT ] 
      │
      ▼
[ SETUP RALPH ] ◄────┐
      │              │
      ▼              │
[ READ STATE  ]      │ (NOT DONE)
      │              │
      ▼              │
[ EXECUTE TASK ] ────┘
      │
      ▼
[ PROMISE: DONE ] ──► [ FINISH ]
```
