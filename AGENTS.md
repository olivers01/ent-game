# AGENTS.md

Project instructions are shared with Claude Code and live in `CLAUDE.md`. Read it first, then `docs/agents/issue-tracker.md`, `docs/agents/triage-labels.md` and `docs/agents/domain.md`.

Rules that apply to every agent here:

- Never add `Co-Authored-By` lines or any AI/model attribution to commit messages or PR descriptions.
- Commit and push only when the user asks.
- The repo is a scaffold with no application code yet. Do not invent a stack; ask.
- `.githooks/pre-commit` runs TruffleHog on staged changes. Do not bypass it with `--no-verify`.
