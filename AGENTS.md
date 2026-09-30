# AGENTS.md — Second Brain Starter

> Instructions for any AI coding agent (Codex, Claude Code, Cursor, etc.) opened in this repository. `CLAUDE.md` imports this file, so there is a single source of truth.

## What this repo is

A free Agent Skill that builds a personal "second brain": a local Obsidian vault, scaffolded from a short interview. The skill lives in `skills/second-brain-starter/SKILL.md`, with its question lists in `reference/` and file templates in `templates/`. It is distributed as a Claude Code plugin (`.claude-plugin/`) and as a plain skill folder usable by Codex.

## If the user wants to build their second brain

The person talking to you is most likely **not technical**. They downloaded this repo to set up their second brain.

1. Read `skills/second-brain-starter/SKILL.md` and follow it exactly, step by step. Its instructions override your defaults for this task.
2. Talk to them in **French** by default (or the language they write in). Plain words, no jargon, one question at a time.
3. **Never create the vault inside this repository folder.** Ask where they want it (suggest `Documents/Mon-Cerveau`) and create it there. This repo is the installer, not the brain.
4. At the end, tell them clearly: from now on, open their assistant **in the vault folder**, not in this one. That is where `CLAUDE.md` / `AGENTS.md` connect the assistant to their brain.

Trigger phrases include: « monte mon second cerveau », « crée mon second cerveau », "set up my second brain", or simply opening a session here with no other request.

## If you are maintaining the repo

- User-facing docs (`README.md`, `INSTALL.md`, `skills/**`) are in **French**. Keep them plain-language: the audience is non-technical.
- Every vault gets both `CLAUDE.md` and `AGENTS.md` (templates in `skills/second-brain-starter/templates/`). Keep the two in sync — same startup sequence, both pointing to `ai-assistant-instructions.md`.
- Templates copied into the vault's `_templates/` keep Obsidian placeholders `{{date}}` / `{{title}}`; `{Curly}` placeholders are filled by the skill from the interview.
- Any user-visible change: bump `version` in `.claude-plugin/plugin.json` and run `claude plugin validate .` before opening a PR.
- Commits: Conventional Commits, in English.
