The `interval` attribute defines the delay (in ticks) between each automatic activation of a skill **when using the** `TICK` **activator**.

This means the skill will be executed repeatedly every `interval` ticks **as long as the item is held** by the player.

!!! note
    `1 second` = `20 ticks` in Minecraft.

## Example

```yaml
Example_Item:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: TICK
    interval: 20 # Runs every 1 second while the item is held
```

!!! warning
    The `interval` attribute is only applicable when using `activator: TICK`. It will be ignored for other activators.