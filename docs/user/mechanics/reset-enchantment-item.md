---
title: Reset Enchantment Item
date:
  created: 2025-08-05
  updated: 2025-08-06
authors:
- phanisment
---

Removes **all enchantments** from the item in the specified equipment slot.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |

## Example

```yaml
Skills:
- resetenchantmentitem @self
```