# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Current state

The repository is a bare scaffold with no application code, build system, dependencies, or tests yet. `README.md` contains only the title (`project-o13s`). There are no build, lint, or test commands to document. Update this file once source code and tooling are added.

## What exists

- `.github/workflows/trufflehog.yaml`: CI secret scan (TruffleHog, `--only-verified`) that runs on every push and pull request with full git history (`fetch-depth: 0`).
- `.githooks/pre-commit`: local TruffleHog scan of staged changes (`--only-verified --fail --no-update`). Enable it once per clone with `git config core.hooksPath .githooks`. Needs `trufflehog` on PATH.
- `.gitignore`: generic (secrets, env files, tool output, deps, build dirs, OS/editor). Trim or extend once the stack is chosen.
- `.vscode/settings.json`: SonarLint connected mode, bound to SonarCloud project key `olivers01_project-o13s` (connection ID `olivers01`). Code-quality findings for this repo are expected to come from that Sonar project.

## Agent skills

### Issue tracker

Issues live in GitHub Issues for olivers01/project-o13s, via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default five-label vocabulary (needs-triage, needs-info, ready-for-agent, ready-for-human, wontfix). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: one `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.

## Git rules

- Never add `Co-Authored-By` lines or any AI/model attribution to commit messages or PR descriptions.
- Commit and push only when the user asks.
