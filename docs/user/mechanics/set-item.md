---
title: Set Item
date:
  created: 2025-08-06
  updated: 2025-08-06
authors:
- phanisment
---

This mechanic is similar to MythicMobs' `equip` mechanic, but with an important difference: `SetItem` supports external item systems that are integrated with **ItemCaster API**.

This means you can assign custom items from other plugins (like ItemsAdder, Oraxen, Nexo, and MythicMobs) directly through this mechanic.

## Supported `type` formats

The `type` attribute supports the following formats:

| Format                             | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `STONE`                            | Any vanilla Minecraft material (e.g., `DIAMOND_SWORD`, `IRON_HELMET`, etc.) |
| `mythicmobs:<item_id>`             | MythicMobs item (always supported)                                          |
| `itemsadder:<namespace>:<item_id>` | ItemsAdder custom item                                                      |
| `oraxen:<item_id>`                 | Oraxen custom item                                                          |
| `nexo:<item_id>`                   | Nexo custom item                                                            |

## Attributes

| Attribute | Aliases             | Description | Default |
|-----------|---------------------|-------------|---------|
| `slot`    | `s`                 | The equipment slot where the item will be placed. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND` |
| `item`    | `replace`, `i`, `r` | The item ID or type to set. Supports Minecraft material or external item format. | `STONE` |

## Example

```yaml
Skills:
- setitem{s=HAND;t=nexo:forest_axe} @self
```

This will replace the item in the player's main hand with the **Nexo** item `forest_axe`