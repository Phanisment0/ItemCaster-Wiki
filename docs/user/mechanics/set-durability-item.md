---
title: Set Durability Item
date:
  created: 2025-08-06
  updated: 2025-08-06
authors:
- phanisment
---

Sets the durability of the item in the specified equipment slot to a specific value.

> Durability value depends on item type. For example, a diamond sword has max durability of 1561.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `amount`  | `a`     | The durability value to set on the item. | `1` |

## Example

```yaml
Skills:
- setdurabilityitem{a=1500} @self
```