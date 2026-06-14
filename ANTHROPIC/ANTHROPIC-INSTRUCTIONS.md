# ANTHROPIC Instruction for AI Agents

Purpose

Provide concise guidance for editing and contributing Claude-related prompts and notes in the `ANTHROPIC/` folder.

Scope

- Applies only to files in this folder (e.g., CLAUDE-FABLE-5.md) and subitems that document Anthropic/Claude system prompts.

Conventions

- Preserve original file formats (`.md`, `.txt`).
- Prefer minimal, focused edits that clarify intent or correct formatting without altering prompt meaning.
- When adding a new prompt or variant, include a one-line attribution header with the source and date.

Editing Guidelines

1. Link, don't duplicate: reference existing explanations elsewhere in the repo or external sources.
2. Attribution: add a short note at the top of new/updated files indicating what changed and why.
3. Testing: do not add runtime code, CI, or artifacts — this repository is documentation-only.
4. File placement: add Claude-specific content under this folder. Use descriptive filenames and include date/version in the name when appropriate.

Quick Examples

- When editing `CLAUDE-FABLE-5.md`, add a short header like:

  "Source: internal collection — updated 2026-06-14 — clarified intent wording"

- When adding a new prompt variant, create `ANTHROPIC/<name>-YYYYMMDD.md` and link it from `CLAUDE-FABLE-5.md` if related.

Useful Links

- Repository guidance: [AGENTS.md](../AGENTS.md)
- Project README: [README.md](../README.md)
- Current file: [ANTHROPIC/CLAUDE-FABLE-5.md](CLAUDE-FABLE-5.md)

Suggested Next Steps for Agents

- Offer a small indexing skill to tag prompts by intent, tone, and safety constraints.
- Propose lightweight templates for new prompt files to ensure consistent attribution and metadata.

---

Created to help AI agents safely and productively edit Anthropic/Claude-related content.
