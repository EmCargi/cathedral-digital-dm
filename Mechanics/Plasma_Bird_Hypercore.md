# Plasma-Bird Hypercore — The Two-Doctrine Skiff

> **Source:** BESM 4e Chapter 14, pp. 322–323 (Chariot-class hypercore, p. 322).

## The Signature Asset

The demo's signature craft is a **Plasma-Skiff** — a 4m, Size Rank 1 vessel whose hypercore references a captured plasma bird. Two doctrines, one chassis (mirrors Enid's psycho-frame vs psycho-slave):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **GTA Authorized Patrol Skiff** | `cathedral_patrol_skiff` | `{"kind":"stat_mod","acv_bonus":2,"ar":4,"note":"plasma-bird hypercore catalyst (regulated)"}` | Licensed, inspected, legal lane |
| **Privateer Corsair Skiff** | `cathedral_corsair_skiff` | Same stats + `Defect: Wanted (GTA)` | Unlicensed, bounty-hunted, illegal lane |

Both: 20 CP, rank C, `item_type: vehicle`, Size Rank 1 (4m), granted as starting gear (not a market buyout).

## Attributes (both doctrines)

- **Spaceflight 3** (100,000 kph)
- **Armour 2** (AR 10)
- **Weapon 4** (Twin Plasma Cannons)

## Engine Path

One `vehicle` row per doctrine in the `items` table, `effect_json` structured for `models.py` (ACV bonus + AR). No new engine field — exactly the CP-2 rail from Enid.