---
title: Add Durability Item
date:
  created: 2025-08-05
  updated: 2025-08-05
authors:
- phanisment
---

Increases durability of the item in a specified slot, such as the player's hand or inventory.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `amount`  | `a`     | The number of durability item that will be added. | `1` |

## Example

```yaml
Skills:
- adddurabiliyitem{a=10} @self
```

This will increase the durability of the item in the player's main hand by 10.