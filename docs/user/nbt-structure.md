---
date:
  created: 2025-08-4
  updated: 2025-08-5
authors:
- phanisment
---

This section explains the **NBT structure** used by ItemCaster for handling skill data in Minecraft items. NBT is used internally to store and read ability definitions that can be cast from the item in-game.

---

## Structure Format

=== "NBT"

    ```yaml
    minecraft:custom_data: {
      ItemCaster: {
        abilities: [
          {
             skill: <String>,
             activator: <String>,
             cooldown: <Double>,
             sneaking: <Boolean>,
             interval: <Integer>,
             signal: <String>,
             variables: {
              <key>: <value>
            }
          }
        ]
      }
    }
    ```

=== "JSON"

    ```json
    "ItemCaster": {
      "abilities": [
        {
          "skill": <String>,
          "activator": <String>,
          "cooldown": <Double>,
          "sneaking": <Boolean>,
          "interval": <Integer>,
          "signal": <String>,
          "variables": {
            "<key>": <value>
          }
        }
      ]
    }
    ```

!!! note
    The `minecraft:custom_data` namespace is usually written to item NBT using a datapack or commands like `/give` or `/data modify`. All data should be placed under the `ItemCaster` object, with an `abilities` array containing one or more ability objects.

[See Here for full explanation of Attributes](./attributes/index.md)

## Example In /give Command
Here’s an example of how to give an item using this NBT with `/give`:

```mcfunction
/give @s stick[minecraft:custom_data={ItemCaster:{abilities:[{skill:"SummonSkeleton",activator:"LEFT_CLICK"}]}}]
```
> You can use tools like [MCStacker](https://mcstacker.net/) to help you build long NBT-based commands more easily.