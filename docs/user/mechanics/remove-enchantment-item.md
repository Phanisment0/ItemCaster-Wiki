---
title: Remove Enchantment Item
date:
  created: 2025-08-05
  updated: 2025-08-06
authors:
- phanisment
---

Removes a specific enchantment from the item in a specified equipment slot.

## Attributes

| Attribute     | Aliases        | Description | Default |
|---------------|----------------|-------------|---------|
| `slot`        | `s`            | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `enchantment` | `enchant`, `e` | The enchantment to remove. See the list of [Enchantments](../../enum/enchantment.md). | `FIRE_ASPECT` |

## Example

```yaml
Skills:
- removeenchantmentitem{e=SHARPNESS} @self
```