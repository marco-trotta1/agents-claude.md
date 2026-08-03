# Contributing

Add public agent context files that help developers study real workflows.

## Add a source

1. Confirm that the file is public and that its source URL works.
2. Prefer `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, `SKILL.md`, or a directly related context file.
3. Do not add private instructions, leaked prompts, secrets, or personal data.
4. Record the source owner, repository, path, branch, and revision in `research/SOURCES.md`.
5. Add a short attribution note under `people/` or `labs/`.
6. Mark community-derived files under `derived/`.

## Review checklist

- Check the source URL.
- Check the source revision.
- Preserve the source file content.
- Run `git diff --check`.
- Use a Conventional Commit message.
