# Spaceflight & Vacuum Hazard

> **Source:** BESM 4e Chapter 14 (Cathedral — space opera) + `besm-environmental-hazards-ledger`.

## Vacuum as a Dungeon Mechanic

The void is the encounter. Every EVA/void node outside a pressurized ring carries a hazard check:

| Hazard | Check | Fail |
|---|---|---|
| **Hard Vacuum** | Body + Survival vs DV 15 | 10 HP cold/vacuum damage + EP drain (narrative) |
| **Cold Radiation** | Body + Resilient vs DV 14 | 10 EP drain, `Defect: Fragile` trigger |
| **Depressurization** | Mind + Mechanics vs DV 12 | Hull breach — forced retreat to previous node |
| **Zero-G Manoeuvre** | Body + Piloting vs DV 12 | Lost orientation — +1 obstacle next check |

## Spaceflight Skill

`Spaceflight` is a **skill group**, not a new engine mechanic — it maps to `Piloting (Spacecraft)` via the existing `SKILL_STAT_MAP`. The `required_check` uses the standard `{stat, skill, dv, fail_damage}` contract; the "zero-G" flavor is narrative + obstacles, not new code.

## Engine Path

No new code — `required_check` + `besm-environmental-hazards-ledger` + existing `execute_action_check` cover it. Cathedral proves space opera works on the same hazard rails as Enid's storm.