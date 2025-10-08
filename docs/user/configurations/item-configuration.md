---
title: Item Configuration
icon: material/sword-cross
date:
  created: 2025-08-04
  updated: 2025-08-06
authors:
- phanisment
---

ItemCaster no longer uses a separate configuration file like older versions.  
Instead, it now **integrates directly into MythicMobs item configuration**, adding new fields under your existing MythicMobs item files.

You can define abilities and display settings using the following structure:

---

### Location 
Place your item configurations inside:

- `MythicMobs/items/*.yml`  
- or `MythicMobs/packs/<pack_name>/items/*.yml`

## Configuration Structure

```yaml
Example_Item:
  ModelItem: <String>      # Custom Model ID or external model source
  Options:
    HideTooltip: <Boolean> # (1.21+) Hide all tooltips from the item
  Abilities:               # This Map Array is called Ability Attributes
  - skill: <String>        # Mythicmobs Id Skill
    activator: <String>    # Event Trigger for the skill
    cooldown: <Double>     # The cooldown item (in Seconds)
    sneaking: <Boolean>    # Check if player is sneaking or not
    interval: <Integer>    # Delay tick interval, special for `TICK` activator.
    signal: <String>       # 
    variables:             # 
      <key>: <value>
```

[See Here for full explanation of Ability Attributes](../attributes/index.md)

### Model

The `Model` field controls how the item's appearance is handled.

#### Example
```yaml
Example_Item:
  Model: nexo:forest_axe
```

!!! warning
    **Do not set** `Id` or `Material` in the same item entry doing so will override and break the custom model system from ItemCaster.

#### Supported External Items:
- `itemsadder:<namespace>:<item_id>`
- `nexo:<item_id>`
- `oraxen:<item_id>`

### HideTooltip
> Only works in Minecraft 1.21 and newer

When enabled, this option hides all tooltips from the item (e.g. lore, attributes, etc).

```yaml
Options:
  HideTooltip: true
```