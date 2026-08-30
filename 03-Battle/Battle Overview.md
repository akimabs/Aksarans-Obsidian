---
tags: [aksarans, battle]
status: draft
---

# Battle Overview

## Battle goal

Habiskan HP lawan sebelum HP player habis.

Untuk prototype awal, kandidat paling sederhana adalah **shared Party HP**. Ini belum locked.

## Turn flow

```mermaid
flowchart TD
    A[Turn Start] --> B[Read Enemy / Opponent State]
    B --> C[Choose 2-4 Creatures]
    C --> D[Preview Sequence]
    D --> E[Confirm]
    E --> F[Resolve by Speed and Properties]
    F --> G[Apply Damage Guard Break Counter etc]
    G --> H{Battle over?}
    H -- No --> A
    H -- Yes --> I[Rewards / Result]
```

## Fundamental rule

**First creature determines the base action. Later creatures modify it.**

```text
HA + CA
= HA Core + CA Link

CA + HA
= CA Core + HA Link
```

Therefore order matters.

## Why this matters

The system can create many useful actions without manually authoring a unique skill for every possible sequence.
