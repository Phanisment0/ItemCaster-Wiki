---
title: Mechanics List
icon: material/nut
authors:
- phanisment
---

This plugin adds additional skill mechanics to MythicMobs, which can be used directly within your MythicMobs skill configurations.

Currently, MythicMobs provides very limited support for item-related mechanics. This plugin extends that functionality significantly. More mechanics will be added in the future to further enhance item manipulation capabilities within skills.

Learn more about MythicMobs mechanics [here](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/Skills/mechanics)

| Mechanic                                                       | Description                                                                                                                                                         |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [AddAmountItem](./add-amount-item.md)                          | Increases the amount of the item held in the player's hand or inventory.                                                                                            |
| [RepairItem](./repair-item.md)                                 | Repairs the item by increasing its durability value.                                                                                                                |
| [AddEnchantmentItem](./add-enchantment-item.md)                | Adds an enchantment to the item.                                                                                                                                    |
| [ReduceAmountItem](./reduce-amount-item.md)                    | Decreases the amount of the item held in the player's hand or inventory.                                                                                            |
| [DamageItem](./damage-item.md)                                 | Damages the item by decreasing its durability.                                                                                                                      |
| [RemoveEnchantmentItem](./remove-enchantment-item.md)          | Removes a specific enchantment from the item.                                                                                                                       |
| [ClearEnchantmentItem](./clear-enchantment-item.md)            | Removes all enchantments from the item.                                                                                                                             |
| [SetAmountItem](./set-amount-item.md)                          | Sets the exact amount of an item in the player's hand or inventory.                                                                                                 |
| [SetDurabilityItem](./set-durability-item.md)                  | Sets a specific durability value on the item.                                                                                                                       |
| [SetItem](./set-item.md)                                       | Replaces the item with an external item supported by ItemCaster. This differs from MythicMobs' built-in `equip` mechanic because it supports custom item providers. |
| [SetCustomModelDataItem](./set-custom-model-data-item.md)      | Sets the custom model data of the item.                                                                                                                             |
| [SetTypeItem](./set-type-item.md)                              | Changes the material type of the item.                                                                                                                              |
| [AddCrossbowProjectile](./add-crossbow-projectile.md)          | Adds a projectile to a crossbow item.                                                                                                                               |
| [AddFoodLevel](./add-food-level.md)                            | Increases the player's food level.                                                                                                                                  |
| [AddFoodSaturationLevel](./add-food-saturation-level.md)       | Increases the player's food saturation level.                                                                                                                       |
| [GiveItem](./give-item.md)                                     | Gives an item to the player using ItemCaster-supported item providers.                                                                                              |
| [ReduceFoodLevel](./reduce-food-level.md)                      | Decreases the player's food level.                                                                                                                                  |
| [ReduceFoodSaturationLevel](./reduce-food-saturation-level.md) | Decreases the player's food saturation level.                                                                                                                       |
| [RemoveHandActivator](./remove-hand-activator.md)              | Removes the active hand activator from the player.                                                                                                                  |
| [SetFoodLevel](./set-food-level.md)                            | Sets the player's food level to a specific value.                                                                                                                   |
| [SetFoodSaturationLevel](./set-food-saturation-level.md)       | Sets the player's food saturation level to a specific value.                                                                                                        |
| [ConsumeMana](./consume-mana.md)                               | Consumes mana from the player.                                                                                                                                      |
| [IncreaseMana](./increase-mana.md)                             | Increases the player's current mana.                                                                                                                                |
| [SetHandCaster](./set-hand-caster.md)                          | Sets the active hand caster for the player.                                                                                                                         |
| [SetMana](./set-mana.md)                                       | Sets the player's current mana.                                                                                                                                     |
| [SetMaxDurability](./set-max-durability.md)                    | Sets the maximum durability value of an item.                                                                                                                       |