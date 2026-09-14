# Orb Radiant Outpost 9

> **Source:** BESM 4e Chapter 14, pp. 322–323 (Cathedral) — invented station detail consistent with canon.

**Type:** Pressurized docking ring on a rogue planetoid at the cluster's edge
**Population:** ~8,000 mixed — GTA inspectors, Xyd pilgrims, privateers, merchants
**Hook:** The 6-node starter's hub (`node_01_dock`)

The neutral ring at the Orb Radiant's edge — the last pressurized handshake before open space. GTA customs postings on one side, Xyd pilgrim hostels on the other, a cantina in the middle where Treaty law and black-market bounties trade at the same table.

**Map:**

```
[node_01_dock] → [node_02_customs] → [node_03_void_breach]
                                        ↘ [node_04_beacon_core]
                                              ↘ [node_05_skiff_skirmish]
                                                    ↘ [node_06_salvage_cache]
```

**Validates as:** `node_type: entrance` (docking ring) — the starting node of `cathedral_waypoint.json`.