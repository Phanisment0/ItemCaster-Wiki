---
title: Add Enchantment Item
date:
  created: 2025-08-05
  updated: 2025-08-06
authors:
- phanisment
---

Adds an enchantment to the item in a specified slot, such as the player's hand or inventory. 

## Attributes

| Attribute    | Aliases       | Description | Default |
|--------------|---------------|-------------|---------|
|`slot`        |`s`            |The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
|`enchantment` |`enchant`, `e` |The enchantment to apply. Use names from the [Enchantment](../../enum/enchantment.md). | `FIRE_ASPECT` |
|`level`       |`l`            |The level of the enchantment to apply. | `1` |

## Example

```yaml
Skills:
- addenchantmentitem{e=SHARPNESS;l=2} @self
```