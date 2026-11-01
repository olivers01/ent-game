# Project context: enterprise gamification class project

Background notes from the planning chat (2026-11-01). Nothing is built yet and no stack is confirmed.

## Open items

Not yet known; ask before planning scope:

- Deadline, and whether the project is solo or group work.
- Any required language, framework or documentation format.
- How it is graded.

## Idea

An onboarding quest app for new hires joining an international team, with a cross-cultural collaboration module (US and Japan) as the showpiece.

Other ideas considered, in order of fit:

1. **Cross-cultural collaboration.** A branching scenario simulator: the player is a US manager working with a Tokyo team, and choices cover feedback, saying no, meetings and missed deadlines. A trust meter shows consequences, and each outcome has a short explanation. Possible extras: a role-swap mode, scored email rewrites, and a two-player mode.
2. **Remote team building.** Cooperative puzzles, weekly quests, a coffee-roulette matcher, and async games that respect time zones. Participation is optional and scoring is team-based.
3. **Remote work motivation and focus.** Voluntary focus sessions, personal streaks and self-reported reflection logs. No screen monitoring, no activity tracking and no time-online rankings.

## Recommended scope

1. **Core:** quest engine with XP, badges and progress, plus an admin page for creating quests and setting point values.
2. **Showpiece:** the US-Japan scenario simulator with 5-8 scenarios.
3. **Extras, only if time allows:** coffee-roulette matching and team goals.

## Mechanics every version needs

- An append-only points ledger (user, event, points, timestamp). Totals and levels are derived from it, so bugs and cheating are traceable.
- A rules table for badges and quests, with conditions stored as data.
- An admin view so managers can configure quests without code.
- Unit tests for the rules engine.

## Proposed stack (unconfirmed)

| Layer | Choice |
|---|---|
| Language | TypeScript |
| Framework | Next.js (React) |
| Database | PostgreSQL |
| ORM | Drizzle or Prisma |
| Auth | Auth.js or Supabase Auth |
| UI | Tailwind CSS with shadcn/ui |
| Hosting | Vercel for the app, Supabase or Neon for Postgres |
| Tests | Vitest for logic, Playwright for one end-to-end flow |

Scenarios are stored as JSON or YAML (nodes, choices, consequences, explanations). Start with multiple-choice scoring. An LLM scoring free-text email rewrites is optional and comes last: it adds API cost, needs rate limiting and a fallback, and its output must be checked.

Python with Django is an alternative that covers auth, ORM and an admin panel in one framework.

## Design and ethics notes

- Present cultural patterns as tendencies with individual variation, and include "it depends" outcomes, to avoid stereotyping. Have someone with real experience review the scenarios if possible.
- Candidate sources for the content: Erin Meyer's *The Culture Map* and Hofstede's dimensions. Verify specifics against the sources before using them.
- Avoid manipulative patterns such as constant leaderboard pressure and mandatory streaks. Address fairness, privacy and burnout in the write-up.
- Reference a design framework (Octalysis or MDA) in the documentation.

## Not verified

- Cultural content comes from general knowledge and has not been checked against the sources.
- Free-tier limits and tool version compatibility have not been checked.
