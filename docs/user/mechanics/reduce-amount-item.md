---
title: Decrease Amount Item
authors:
- phanisment
---

Decreases the amount of the item in a specified slot, such as the player's hand or inventory.

## Attributes

| Attribute | Aliases | Description                                                                                                       | Default |
|-----------|---------|-------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `amount`  | `a`     | The number of items to remove from the item stack.                                                                | `1`     |

## Example

```yaml
Skills:
- reduceamountitem{a=1} @self
```