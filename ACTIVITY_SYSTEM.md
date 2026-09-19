# Engineering activity system

This repository supports a genuine building habit. Only commit when there is a real artifact: code, a tested fix, a documented decision, a solved problem, or a reflection that will be useful later.

## Daily (20–60 minutes)

1. Pick one small, concrete task from an active project or learning goal.
2. Build, test, or study it.
3. Commit only the resulting change. If there is no durable result, do not manufacture a commit.
4. When useful, add a short entry based on `templates/progress-entry.md` under `learning-log/<year>/<month>/`.

Examples of meaningful daily work: add a test case, fix an accessibility issue, complete and document one algorithm problem, improve an example after verifying it, or record a learning note that includes code and sources.

## Weekly (60–120 minutes)

- Ship one focused improvement to an active project.
- Review README accuracy, open issues, and unfinished branches.
- Solve and explain one problem-solving exercise.
- Choose the next smallest shippable task; close or defer stale work explicitly.

## Monthly (2–4 hours)

- Release or substantially improve one project when the work merits it.
- Review the profile’s selected work and remove stale claims.
- Update the scorecard below from evidence, not estimates.
- Write a short retrospective: what shipped, what you learned, and what is next.

## Quality scorecard

Update these manually once per month with links to the underlying work.

| Metric | Current evidence | Next review |
| --- | --- | --- |
| Actively maintained repositories | Add repository links | 2026-10 |
| Releases | Add release links | 2026-10 |
| Issues / pull requests | Add GitHub links | 2026-10 |
| Documentation improvements | Add commit or PR links | 2026-10 |
| Tests added | Add commit or PR links | 2026-10 |
| Technologies practised | Add project or note links | 2026-10 |
| Open-source contributions | Add merged PR links | 2026-10 |

## Automation boundary

Automation may validate documentation and project health, but it must not create placeholder progress entries, fake learning summaries, or empty commits. The scheduled workflow in `.github/workflows/docs-check.yml` checks that this system remains structurally usable; it never writes to the repository.
