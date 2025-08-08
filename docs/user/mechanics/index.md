---
title: Mechanics List
icon: material/nut
date:
  created: 2025-08-05
  updated: 2025-08-05
authors:
- phanisment
---

This plugin adds additional skill mechanics to MythicMobs, which can be used directly within your MythicMobs skill configurations.

Currently, MythicMobs provides very limited support for item-related mechanics. This plugin extends that functionality significantly. More mechanics will be added in the future to further enhance item manipulation capabilities within skills.

Learn more about MythicMobs mechanics [here](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/Skills/mechanics)

| Mechanic | Description |
|----------|-------------|
| [AddAmountItem](./add-amount-item.md) | Increases the amount of the item held in the player's hand or inventory. |
| [AddDurabilityItem](./add-durability-item.md) | Repairs the item by increasing its durability value. |
| [AddEnchantmentItem](./add-enchantment-item.md) | Adds an enchantment to the item. |
| [DecreaseAmountItem](./decrease-amount-item.md) | Decreases the item amount from the player's hand or inventory. |
| [DecreaseDurabilityItem](./decrease-durability-item.md) | Damages the item by decreasing its durability. |
| [RemoveEnchantmentItem](./remove-enchantment-item.md) | Removes a specific enchantment from the item. |
| [ResetEnchantmentItem](./reset-enchantment-item.md) | Clears all enchantments from the item. |
| [SetAmountItem](./set-amount-item.md) | Sets the exact amount of an item in the player's hand or inventory. |
| [SetDurabilityItem](./set-durability-item.md) | Sets a specific durability value to the item. |
| [SetItem](./set-item.md) | Replaces the item with an external item supported by ItemCaster. This mechanic is different from MythicMobs' built-in `equip` mechanic as it supports integration with custom item providers. |
| [SetModelDataItem](./set-model-data-item.md) | Sets the custom model data of the item for resource pack usage. |
| [SetTypeItem](./set-type-item.md) | Changes the material type of the item (e.g., from `STONE` to `DIAMOND_SWORD`). |
