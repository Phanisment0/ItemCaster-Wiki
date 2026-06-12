---
title: Item Configuration
icon: material/sword-cross
date:
authors:
- phanisment
---

How you configure is the same as the item but with its own config, located in `ItemCaster/hand`. How this works is you don't need an item to cast the skill, but the player itself contains the skill data ability, which only allows 1 right now.

---

## Location
Place your config in here:
- `ItemCaster/hand`

Id hand activator will like this:
- <file name>:<id>

Pattern for valid ID: [0-9a-z_]:[0-9a-z-_./]

```yaml title="ItemCaster/hand/example_hand.yml"
<Id>:
  conditions:
  - <Conditions>
  abilities:
  - <Attribute>
```

[See here for a full explanation of ability attributes.](../attributes/index.md)

For conditions is use same as [condition](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/home) in config skill mythicmobs.

### Example

```yaml
example:
  conditions:
  - hasAura{n=test_aura} true
  abilities:
  - skill: example_skill
    activator: left_click
```