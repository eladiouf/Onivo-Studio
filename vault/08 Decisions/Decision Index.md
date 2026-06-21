# Decision Index

This page indexes important studio and project decisions.

## Catalogue (manual fallback, also available via Dataview)

| Id | Date | Area | Subject |
|---|---|---|---|
| `STUDIO-DEC-001` | 2026-06-21 | governance | Studio autonomy expansion (Founder Amendment) |
| `STAT-DEC-001` | 2026-06-21 | platform-identity | NeoForge 1.21.1 runtime truth |
| `STAT-DEC-002` | 2026-06-21 | integration-policy | Epic Fight reclassified as experimental optional |
| `STAT-DEC-003` | 2026-06-21 | intelligence-process | Mahou + Elementals removal postmortem opened |
| `STAT-DEC-004` | 2026-06-21 | studio-operations | STAT Mod onboarding into Onivo Studio complete |
| `STAT-DEC-005` | 2026-06-21 | documentation-taxonomy | `docs/superpowers/plans/` canonical, `.opencode/plans/` deprecated |
| `STAT-DEC-006` | 2026-06-21 | delivery-sequencing | Mission prioritization sequence locked |

## Dataview (auto)

```dataview
TABLE date, area, status, related_projects
FROM "vault/08 Decisions"
WHERE type = "decision" AND file.name != "Decision Index"
SORT date DESC
```

## Meetings

| Id | Date | Type |
|---|---|---|
| `STAT-MTG-001` | 2026-06-21 | Plenary — Milestone Review + Exception Council |
