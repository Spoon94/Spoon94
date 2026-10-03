# Spoon

**AI Navigator** · learning AI, specializing in **AI Harness**

I build tooling for **AI coding agents** — skill collections, CLI utilities, and knowledge systems that make day-to-day work with agents faster.

---

## Projects

### 📦 [skill-vault](https://github.com/Spoon94/skill-vault)

**63 curated [Agent Skills](https://agentskills.io/specification)** for Claude Code, Codex CLI, Copilot CLI, Gemini CLI and OpenCode — each one a self-contained `SKILL.md` you can drop into any compatible agent.

| Group | What's in it |
| --- | --- |
| **Explain & draw** (14) | `eli5` · `show-me` · `clarify` · `falsify` · 7 × `diagram-*` |
| **Dev workflow** (19) | brainstorming · writing plans · TDD · systematic debugging · code review · git worktrees |
| **Retrieval** (5) | code-semantic search · web extraction · GitHub · session history |
| **Notes & memory** (6) | Obsidian batch rendering · cross-session memory |
| **Ops & integrations** (6) | tmux · herdr · opencli · mcp2cli |
| **Docs & design** (12) | docx · pdf · pptx · xlsx · canvas · frontend design |

The core thread is a pipeline — **explain** (`show-me` / `eli5`) → **render** (`diagram-*`) → **stress-test** (`falsify`) → **tone** (`clarify` / `deslop-bi`).

![skill map](https://raw.githubusercontent.com/Spoon94/skill-vault/main/docs/images/skill-map.svg)

### 🦦 [cli-zoo](https://github.com/Spoon94/cli-zoo)

A small zoo of shell tools for AI-coding workflows. One tool per animal, symlink-installed to `$PREFIX`.

| Tool | What it does |
| --- | --- |
| **otter** | Spins up a tmux session with your AI CLI, yazi, nvim and lazygit in one layout — one command into a working setup. |
| **wren** | Two-line Dracula statusline (tokens, cache hit rate, compaction count, context usage). Installs into **four hosts** — Claude Code, pi, Qoder CLI and opencode. |

![wren statusline](https://raw.githubusercontent.com/Spoon94/cli-zoo/main/docs/wren-preview.svg)
