# Anthropic Prompt File Template

Use this lightweight template when adding or documenting prompts in the `ANTHROPIC/` folder. Save new files using the pattern `<short-name>-YYYYMMDD.md`.

---

Title: Short descriptive title
Source: original source or collection name
Author: Your name or initials
Date: 2026-06-14
Version: 1.0

Intent: A one-line statement of the prompt's intended purpose (e.g., "summarize technical docs for non-experts")
Tone: e.g., `concise`, `friendly`, `formal`, `storybook`
SafetyConstraints: Brief note about sensitive topics or content to avoid

Prompt:
```
<Insert the prompt text exactly as intended for use>
```

UsageExample:
```
System: <system instruction, if any>
User: <example user message>
Assistant: <expected model behavior or example completion>
```

Attribution:
- File: `ANTHROPIC/CLAUDE-FABLE-5.md`
- Notes: Short explanation of changes or provenance

ChangeLog:
- 2026-06-14 — v1.0 — created by AI agent

Guidelines:
- Keep edits minimal and preserve original intent.
- Add a single-line attribution header at the top of the file when you create or modify it.
- Link related prompt files rather than duplicating content.
