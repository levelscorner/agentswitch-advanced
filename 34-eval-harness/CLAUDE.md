@AGENTS.md

## Claude Code notes
- Start Claude Code from inside `34-eval-harness/`, so this file and `AGENTS.md` load.
- Personal preferences belong in `CLAUDE.local.md` (git-ignored) or your own memory, never in this file.
- For parallel sessions, use `claude -w <name>` or a git worktree per session. A fresh worktree needs `.env` copied in, then `uv sync`.

## Agent skills

### Issue tracker
Work is tracked as cards in `docs/processed/project/board.md`, not GitHub Issues. See `docs/agents/issue-tracker.md`.

### Triage labels
The five default labels, written as tags on a board card. See `docs/agents/triage-labels.md`.

### Domain docs
Single-context: `docs/processed/glossary.md` and `docs/processed/decisions/`. See `docs/agents/domain.md`.
