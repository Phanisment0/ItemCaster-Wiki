---
title: Add Amount Item
date:
  created: 2025-08-05
  updated: 2025-08-05
authors:
- phanisment
---

Increases the amount of the item in a specified slot, such as the player's hand or inventory. This mechanic is useful for giving additional items as part of a skill.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `amount`  | `a`     | The number of items to add to the item stack. | `1`     |

## Example

```yaml
Skills:
- addamountitem{a=2} @self
```

This will increase the amount of the item in the player's main hand by 2.