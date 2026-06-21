---
type: risk
status: Open
severity: S2-High
owner: Product Cell
date: 2026-06-21
next_review: 2026-06-22
related_projects:
  - STAT Mod
tags:
  - risk
  - statmod
---

# 2026-06-21 - STAT Mod Runtime Identity Drift

## Description

The active branch and build files indicate `NeoForge 1.21.1`, while parts of the public-facing project identity still describe the older Forge 1.20.1 line.

## Impact

Players, testers, and future agents can act on the wrong runtime assumptions.

## Signals

- root `README.md` still advertises Forge 1.20.1
- `gradle.properties` and `build.gradle` target NeoForge 1.21.1

## Mitigation

- execute [[2026-06-21 - STAT Mod Release Identity Alignment Mission]]
- keep [[2026-06-21 - STAT Mod NeoForge Runtime Truth]] as the current operating decision

## Escalation

Escalate if code, metadata, and release surfaces still disagree after the alignment pass.
