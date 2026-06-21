---
type: risk
status: Open
severity: S1-Critical
owner: Verification Cell
date: 2026-06-21
next_review: 2026-06-22
related_projects:
  - STAT Mod
tags:
  - risk
  - statmod
---

# 2026-06-21 - STAT Mod Multi-Mod Integration Regression

## Description

`STAT Mod` now depends on a growing set of combat, perk, race, and magic integration surfaces that can regress each other.

## Impact

An apparently local change can break combat, perk routing, gating, or runtime compatibility across integrated mods.

## Signals

- dedicated integration tests already exist for Epic Fight, Puffish, Tensura, Overgeared, and magic subsystems
- optional-mod support relies on compat layers and mixins

## Mitigation

- execute [[2026-06-21 - STAT Mod Verification Baseline Sweep Mission]]
- keep major integrations behind explicit compat surfaces

## Escalation

Escalate if verification cannot isolate which integration family is currently failing.
