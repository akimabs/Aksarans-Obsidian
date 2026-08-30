---
tags: [aksarans, battle, properties]
status: draft
---

# Combat Properties

These are **actions/properties**, not elemental types.

## Minimal candidate set

### Attack

Reduces enemy HP.

### Guard

Reduces incoming damage.

### Break

Answers defensive/committed states such as Guard or Charge.

### Charge

A strong action that gives the opponent a response window.

### Counter / Tanggah

Responds when receiving a compatible enemy action.

### Speed

Determines which action resolves first where relevant.

## Counter relationships

Working example:

```text
Enemy Guard
-> Break is efficient

Enemy Charge
-> Break / fast interrupt is efficient

Enemy Attack
-> Guard / Tanggah is efficient
```

This is deliberately not a strict universal rock-paper-scissors table.

## Why no elements yet

Adding element types would force players to learn another counter language on top of Core/Link/sequence/order. Only add elements later if creature identity or content variety genuinely needs it.
