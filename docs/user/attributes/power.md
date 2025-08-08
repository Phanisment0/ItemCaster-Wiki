The `power` attribute acts as a **multiplier** that affects damage and other power-scalable mechanics inside your skill.

This is directly integrated with MythicMobs' internal power system.

!!! note
    For full documentation and behavior details, see the official MythicMobs guide on [Power Scaling](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/mobs/Power)

---

## Example

```yaml
Example:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
    power: 2
```

In this example, any damage or power-based effects within the skill will be **doubled** (`2x` multiplier).