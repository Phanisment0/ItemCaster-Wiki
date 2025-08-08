---
title: Decrease Amount Item
date:
  created: 2025-08-05
  updated: 2025-08-06
authors:
- phanisment
---

Decreases the amount of the item in a specified slot, such as the player's hand or inventory.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `amount`  | `a`     | The number of items to remove from the item stack. | `1` |

## Example

```yaml
Skills:
- decreaseamountitem{a=1} @self
```