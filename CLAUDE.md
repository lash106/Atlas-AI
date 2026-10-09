@AGENTS.md

# Claude Code notes

- `AGENTS.md` (imported above) holds the shared rules for every AI tool. Add Claude-specific guidance here only.
- At the start of a task, confirm which module and which `SPEC.md` section 18 task you are working on, then read only the `SPEC.md` sections that apply instead of the whole file.
- For anything touching more than one file or any contract, enum, or policy rule, propose a short plan first and wait for approval.
- Run `make test lint typecheck` before declaring a task finished and report the actual output, including failures.
- Prefer writing the failing test first for policy, memory, and metric code.
- Personal preferences go in `CLAUDE.local.md` (git-ignored), not in this file.
