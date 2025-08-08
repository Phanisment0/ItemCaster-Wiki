The `signal` attribute is used to check whether a signal string matches the one sent by a signal mechanic.

You can see the official MythicMobs documentation for the signal mechanic [here](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/skills/mechanics/signal).

When the player receives a signal (via MythicMobs mechanic), the ability with matching `activator: SIGNAL` and `signal: <value>` will be executed.

---

## Example

If you trigger this mechanic:

```
/mm t m signal{s=example_signal} @self
```

It will activate any ability on the player's item that matches `activator: SIGNAL` and has `signal: example_signal`.

```yaml title="MythicMobs/items/example_item.yml"
Example:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: SIGNAL
    signal: example_signal
```

!!! note
    If the `activator` is `SIGNAL` but the `signal` attribute **is not set**, the ability will be triggered **by any signal** applied to the player.