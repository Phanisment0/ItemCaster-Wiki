---
title: Clear Enchantment Item
authors:
- phanisment
---

Removes **all enchantments** from the item in the specified equipment slot.

## Attributes

| Attribute | Aliases | Description                                                                                                       | Default |
|-----------|---------|-------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |

## Example

```yaml
Skills:
- clearenchantmentitem @self
```

## Aliasses

- itemcaster:clearenchantmentsitem
- itemcaster:clearenchantments
- clearenchantmentsitem
- clearenchantments
- clearenchant