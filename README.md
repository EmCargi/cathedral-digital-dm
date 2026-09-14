# 💿 Cathedral: Orb Radiant — Game Disc for Chronos Core

*Disc 6 — the second Anime Multiverse Prime World.* Space opera, void combat, plasma birds.

> **Source:** BESM 4e Chapter 14, pp. 322–323 (Cathedral) + Ch.3 Race Templates (Greys p.42, Woolies p.55). First-party canon.
> All content authored from the canon hooks. 85%-applicable spec — engine-free.

---

## 🎮 Boot

```text
/setting besm_cathedral    # swap discs in the TUI
/roster                    # Security Clearance column (Pilot/Inspector/Scrapper/Emissary/Laborer/Corsair)
/module cathedral_waypoint  # default: 6-node starter (Dock → Customs → Void Breach → Beacon → Skirmish → Salvage)
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_cathedral` in `config/settings.json` → `cathedral_waypoint.json` |
| **2 · Module** | ✅ `cathedral_waypoint.json` (6 nodes, validator-passed) |
| **3 · Roster** | ✅ 6 starter characters (Caelen Vhol through Rixia Talon, 50 CP, `besm_cathedral`) |
| **4 · Economy** | ✅ seed catalog + 2-doctrine Plasma-Skiff (vehicle, 20 CP) |
| **5 · Lore Vault** | 🏗️ `World/` `Factions/` `Locations/` `Mechanics/` `Characters/` |

## 🗂️ Structure

```
cathedral-digital-dm/
├── README.md               ← this home page
├── World/                  ← Orb Radiant, Plasma Birds, Treaty of Cathedral
├── Factions/               ← GTA, Fusion, Xyd/Taj Kehal, Privateers
├── Locations/              ← Outpost 9, Cathedral Wayline Relay
├── Mechanics/              ← Spaceflight/Vacuum, Plasma-Bird Hypercore
├── Characters/             ← 6 starter sheets (50 CP)
├── modules/                ← cathedral_waypoint.json (6-node authoring source)
└── scripts/build_cathedral_disc.py ← regenerable build (sole atomic writer)
```

## 🚀 The Pitch

The Orb Radiant — 100,000 stars, one nesting ground of hyperspatial plasma birds, and the Treaty that made them sacred. GTA customs against privateer bounty-hunters, Xyd pilgrims guarding the gate nexus, and a Grey emissary who reads the wayline beacon. The void is the enemy before the enemy.

## 📌 Why Cathedral is Disc 6

Enid proved ground-bound psychic mecha. Cathedral flips the physics stack: zero-G, vacuum hazard, plasma weaponry, space piracy — the console's widest genre swing yet, with zero engine edits.

---
*Swap the disc, keep the console.*