---
title: Item Configuration
icon: material/sword-cross
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

```yaml title="MythicMobs/items/example_items.yml"

Example_Item:
  ModelItem: <String>      # Custom Model ID or external model source
  
  Options:
    HideTooltip: <Boolean> # (1.21+) Hide all tooltips from the item
  
  Abilities:               # This Map Array is called Ability Attributes
  - <Attribute>

```

[See here for a full explanation of ability attributes.](../attributes/index.md)

### ModelItem

The `ModelItem` field controls how the item's appearance is handled.

#### Example
```yaml
Example_Item:
  ModelItem: nexo:forest_axe
```

#### Supported External Items:
- `itemsadder:<namespace>:<item_id>`
- `nexo:<item_id>`
- `oraxen:<item_id>`
- `craftengine:<item_id>`

### HideTooltip
> Only works in Minecraft 1.21 and newer

When enabled, this option hides all tooltips from the item (e.g. lore, attributes, etc).

```yaml
Options:
  HideTooltip: true
```