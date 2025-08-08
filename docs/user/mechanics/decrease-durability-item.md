---
title: Decrease Durability Item
date:
  created: 2025-08-05
  updated: 2025-08-06
authors:
- phanisment
---

Decreases the durability of the item in a specified slot, such as the player's hand or equipment slot. This can simulate damage or usage on an item when a skill is triggered.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `amount`  | `a`     | The number of durability points to decrease. | `1` |

## Example

```yaml
Skills:
- decreasedurabilityitem{a=5} @self
```