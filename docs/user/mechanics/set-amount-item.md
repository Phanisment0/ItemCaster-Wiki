---
title: Set Amount Item
date:
  created: 2025-08-06
  updated: 2025-08-06
authors:
- phanisment
---

Sets the item amount in a specified equipment slot to a specific number.

## Attributes

| Attribute | Aliases | Description | Default |
|-----------|---------|-------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `amount`  | `a`     | The number to set the item amount to. | `1` |

## Example

```yaml
Skills:
- setamountitem{a=5} @self
```