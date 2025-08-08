---
title: Home
icon: material/home
date:
  created: 2025-08-4
  updated: 2025-08-4
authors:
- phanisment
---

![Preview](../../assets/images/preview.png)
![Separator](../../assets/images/separator.png)

!!! note
    This plugin is still under development. Features and configurations may change in the future as new functionality is added.

# Introduction

ItemCaster is a free alternative to plugins like [MythicCrucible](https://mythiccraft.io/index.php?resources/crucible-custom-items-armor-furniture-blocks-more.2/) or [MMOItems](https://www.spigotmc.org/resources/mmoitems.39267/). and has more customization for users.

***

## Simple Usage Example

To begin, create a generic MythicMobs item. [You can refer to the official MythicMobs item guide here](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/Items/Items).

Then configure your item like this:

```yaml title="MythicMobs/items/Example_Item.yml"
Example_Item:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
```

As shown above, the `Abilities` section defines the skill and the trigger (in this case, `left_click`) for the item.

For List of Activator, you can see it in [here](user/activator-list.md).