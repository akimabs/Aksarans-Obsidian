---
tags: [aksarans, battle, combo]
status: draft
---

# Combo System

## Input

Party size: max 5 creature.

Sequence size per action: **2-4 creature**.

> [!question]
> Apakah sequence 1 creature diperbolehkan sebagai fallback/basic action? Belum diputuskan.

## Composition

```text
Slot 1 = CORE
Slot 2 = LINK
Slot 3 = LINK
Slot 4 = LINK
```

Example placeholder:

```text
HA + NA + CA

HA Core   -> attack
NA Link   -> add guard
CA Link   -> add break
```

## Combo length

Working model:

| Length | Default speed | Character |
|---:|---|---|
| 2 | Fast | simple response |
| 3 | Normal | flexible action |
| 4 | Slow | high utility / high commitment |

Speed can be modified by creature Link effects.

This prevents "always use 4" from becoming optimal.

## Desired mastery curve

Early player:

> "CA berarti Break."

Intermediate:

> "HA + CA = fast attack with Break."

Advanced:

> "HA + CA + RA adalah sequence yang kupakai untuk interrupt Charge sebelum resolve."

The end goal is muscle memory rather than reading tooltips forever.
