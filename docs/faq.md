
## How to reload ItemCaster?
Use the reload command from MythicMobs `/mm r`.

## Can an item have multiple abilities?
It is.

Like this:
```yml
Example:
  Abilities:
  - skill: skill_1
    activator: left_click
```

Become this

```yml
Example:
  Abilities:
  - skill: skill_1
    activator: left_click
  - skill: skill_2
    activator: right_click
  - skill: skill_3
    activator: damaged
```

## Why is the item appearance in the MythicMobs menu not applied when the ItemCaster menu is shown?
Because MythicMobs make an item cached for the menu when loaded, not when you create the new instance of MythicItem.

The simple reason is that the item menu and the given item are not the same.