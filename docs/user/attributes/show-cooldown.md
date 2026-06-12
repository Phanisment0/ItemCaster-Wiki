The attribute `show_cooldown` will show the cooldown of the activated skill on the player action bar message.

The action bar message will show even if you use cooldown on skill config cooldown.

I have a plan for you to have more customization with the PlaceholderAPI, but for now it's just hardcoded in plugins.

---

## Example

```yaml title="MythicMobs Skill Config"
Example:
  Cooldown: 10
  Skills:
  - message{m=pass}
```

```yaml title="On Ability attribute"
Example_item:
  Id: stick
  Abilities:
  - skill: Example
    activator: left_click
    cooldown: 5 # this will override `cooldown` in skill config
    show_cooldown: true
```