# Branching Model

This repository uses a simple branch model:

- `master`: production-ready branch
- `feature/<name>`: new work
- `fix/<name>`: bug fixes
- `codex/<name>`: optional branches for Codex-specific tasks

## Workflow

1. Branch from `master`.
2. Use one of the approved prefixes.
3. Open a pull request back into `master`.
4. Merge only after checks/review pass.

## Examples

- `feature/add-airtable-sync`
- `fix/login-timeout`
- `codex/refactor-table-mapping`
