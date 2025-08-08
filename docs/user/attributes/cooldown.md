Defines the cooldown **(in seconds)** between each skill activation. This prevents the skill from being triggered repeatedly in a short period.

!!! important
    You must set the MythicMobs skill's `Cooldown` to `0` in your skill configuration. Otherwise, the `cooldown` attribute in this plugin **will not work**, due to how MythicMobs handles internal cooldowns.

---

## Example

```yaml title="MythicMobs/skills/example_skill.yml"
Example_Skill:
  Cooldown: 0
  Skill:
  - # Your mechanic here
```

```yaml title="MythicMobs/items/example_item.yml"
Example_Item:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
    cooldown: 10
```