---
title: Set Type Item
date:
  created: 2025-08-06
  updated: 2025-08-06
authors:
- phanisment
---

Changes the **material type** of the item in the specified slot.  

## Attributes

| Attribute  | Aliases          | Description | Default |
|------------|------------------|-------------|---------|
| `slot`     | `s`              | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `material` | `type`, `m`, `t` | The new material type for the item. Must be a valid [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html) name. | – |

## Example

```yaml
Skills:
- settypeitem{s=HAND;type=DIAMOND_SWORD} @self
```