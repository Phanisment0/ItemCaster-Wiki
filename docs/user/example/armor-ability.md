---
title: Armor Ability Example
icon: fontawesome/solid/shirt
date:
  created: 2025-08-06
  updated: 2025-08-06
authors:
- phanisment
---

<video controls>
	<source src="assets/videos/armor_ability.mp4" type="video/mp4">
</video>

Abilities can also be assigned to **armor items**, not just to items held in hand. This allows you to trigger special effects or skills when a player wears specific armor pieces.

However, **not all activators are supported** for armor. Activators that rely on item-specific interactions from Bukkit events (such as `BOW_SHOOT`) are **not supported** when the item is worn as armor.

You can refer to this [`ActivatorListener`](https://github.com/Phanisment0/ItemCaster/blob/main/src/main/java/io.phanisment.itemcaster/listener/ActivatorListener.java) class. If an event handler does **not** utilize [`ItemUtil`](https://github.com/Phanisment0/ItemCaster/blob/main/src/main/java/io.phanisment.itemcaster/util/ItemUtil.java), it is not compatible with armor equipment.

## Example

```yaml
Example_Armor:
  Id: IRON_CHESTPLATE 
  Abilities:
  - skill: berserk
    activator: DAMAGED
```

In this example:

- When the player **takes damage** while wearing the `IRON_CHESTPLATE`, the skill `berserk` will be triggered.
- The `DAMAGED` activator is one of the supported activators for armor items.

## Download Full Example
To help you understand better, I provided a **ready-to-use example configuration** you can test directly.

[ :material-download: Download ](../../assets/example/armor-ability.zip){:download .md-button}