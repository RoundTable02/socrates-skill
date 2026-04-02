# Socrates Skill

**Never answers. Always asks.** A Socratic method teaching skill that guides you to discover answers through questioning — for any knowledge asset.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Open%20Standard-blue?style=for-the-badge)](https://skills.sh)

## Quick Install

```bash
npx skills add RoundTable02/socrates-skill
```

<details>
<summary>Other installation methods</summary>

**Claude Code**

```bash
claude install-skill RoundTable02/socrates-skill
```

**Manual (Git clone)**

```bash
git clone https://github.com/RoundTable02/socrates-skill.git ~/.claude/skills/socrates
```

</details>

## What It Does

Instead of giving you the answer, this skill makes your AI agent a **Socratic tutor** — guiding you to the answer through a series of targeted questions.

Works with **any knowledge asset**:

- Source code & codebases
- Markdown / PDF / DOCX documents
- API documentation
- Configuration files
- Architecture diagrams
- Any readable content

## Trigger

Include any of these keywords in your message:

| Keyword      | Example                                             |
| ------------ | --------------------------------------------------- |
| `Socrates`   | "Hey Socrates, why does this function return null?" |
| `socratic`   | "Socratic mode — walk me through this auth flow"    |
| `소크라테스` | "소크라테스님, 이 문제는 어떻게 풀어야 할까요?"     |

## Usage Examples

```
Socratic: help me understand the authentication flow in this codebase
```

```
Use socratic method to explore the performance issues in this code
```

```
Socrates — guide me through this PDF paper's core argument
```

## How It Works

The skill follows a 5-step questioning workflow:

1. **Read** — Silently analyzes the target resource
2. **Assess** — Asks an opening question to gauge your understanding
3. **Guide** — Progressively deeper questions (clarifying → probing → connecting → counter → hypothetical)
4. **Adapt** — Adjusts based on your responses (simplifies, deepens, or redirects)
5. **Confirm** — Asks you to summarize your understanding

### Core Rule

> The agent **never** gives a direct answer — even if you ask for one.

## Language

Automatically mirrors your language. The agent detects and responds in whatever language you write in.

## License

MIT
