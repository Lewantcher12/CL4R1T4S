# AGENTS.md

## Purpose

Short guidance for AI coding agents working in this repository. CL4R1T4S is a curated collection of prompts, system instructions, and notes organized by vendor/platform; it is documentation-first and contains no build or test infrastructure.

## Structure

- Files are organized by vendor/platform (e.g. [ANTHROPIC/](ANTHROPIC/), [OPENAI/](OPENAI/), [GOOGLE/](GOOGLE/)).
- Content types: `.md`, `.mkd`, and `.txt` files containing prompts and notes.

## Quick Rules for Agents

1. Minimal edits: prefer small, focused contributions and preserve original file formats.
2. Link, don't duplicate: reference existing docs (see [README.md](README.md)) instead of embedding large sections.
3. No build or test scaffolding: this repository is docs-only — do not create CI, package.json, Makefiles, or similar unless explicitly requested.
4. Respect vendor folders: add new content to the appropriate vendor subdirectory.
5. Attribution: when adding or transforming prompts, include a brief note linking to the source file.

## Useful Links

- Repository README: [README.md](README.md)

## Suggested Next Agent Customizations

- Create a focused instruction for the `ANTHROPIC/` folder to guide Claude-related edits.
- Create a skill that helps index and surface prompts by intent or capability.

---

Generated/updated by AI agent to help subsequent agents start productively in this repo.
