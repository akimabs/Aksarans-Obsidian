---
tags: [aksarans, ux, battle]
status: draft
---

# Battle UX

## Landscape direction

Recommended hierarchy:

```text
+-------------------------------------------------------------+
|                           BATTLE                            |
|                                                             |
|                      opponent / enemy                       |
|                                                             |
|                      player creature                        |
|                                                             |
|                 [slot][slot][slot][slot]                    |
|                                                             |
|           HA       NA       CA       RA       KA            |
|        creature creature creature creature creature         |
|                                                             |
|                        [ CONFIRM ]                          |
+-------------------------------------------------------------+
```

Only the five party creature need to be battle inputs. Do **not** display all 20 during battle if party is limited to five.

## Input feedback

When a creature is tapped:

1. it enters the next sequence slot,
2. preview updates immediately,
3. game shows resulting properties in compact form.

Example:

```text
HA -> CA -> RA
22 DMG | BREAK | FAST
```

## PvE telegraph

Enemy intent icon sits near/above enemy and is readable before selection.

## PvP telegraph

Do not show full current sequence before both players commit. See [[05-PvP/PvP Rules]].
