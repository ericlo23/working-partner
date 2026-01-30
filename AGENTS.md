# Repository Guidelines

## Project Structure & Module Organization
This repository stores documentation for the AI Working Partner. There is no source code or build system.
- `instructions.md`: Core behavior, capabilities, and interaction style.
- `project-management.md`: ClickUp and task lifecycle rules.
- `operating-cadence.md`: Weekly/daily routines and check-ins.
- `README.md`: Short repo purpose statement.

Keep files small and focused. When a section grows, split it into a dedicated file and link it from `instructions.md` under **Index**.

## Build, Test, and Development Commands
There are no build or test commands for this repo. Changes are made directly to Markdown files. Example:
```sh
rg -n "" instructions.md
```

## Coding Style & Naming Conventions
Markdown only. Keep wording concise and directive.
- Headings use `#` / `##` for structure.
- Bullet lists use `-` and stay action-oriented.
- File names are kebab-case, e.g., `project-management.md`.

## Testing Guidelines
No automated tests. Validate by reading for clarity and consistency across files. If you split content, ensure links in `instructions.md` Index are updated.

## Commit & Pull Request Guidelines
Commit messages follow conventional commits format: `type(scope): description`. Examples:
- `docs(instructions): restructure instructions and split cadence/tasks`
- `docs: document repo purpose`
- `feat(cadence): add weekly review template`

Common types: `feat`, `fix`, `docs`, `refactor`, `chore`.

PRs should include:
- A brief summary of what changed and why.
- Any moved/renamed files with updated references.

All commits should include a Co-Authored-By trailer with the AI assistant's identity.

## Agent-Specific Instructions
When editing, preserve the meaning of existing guidance. Prefer restructuring and clarifying over rewriting. If introducing new rules, keep them minimal and consistent with the current tone.
