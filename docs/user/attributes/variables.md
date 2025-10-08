The `variables` attribute allows you to define **custom skill variables** for a MythicMobs skill directly in the item's ability.

This uses the **MythicMobs API**, and works just like regular skill variables but can be customized per item, making it much more convenient and flexible.

You can define **one or more variables** using this system, depending on the needs of your skill.

!!! tip
    Learn more about skill variables in the [MythicMobs Wiki – Skill Variables](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/Skills/Variables)

---

## Example

```yaml title="MythicMobs/skills/example_skill.yml"
Example_Skill:
  Skills:
  - damage{amount=<skill.var.damage>} @self
  - message{m=<skill.var.message>} @self
```

```yaml title="MythicMobs/items/example_items.yml"
Example_Item:
  Id: STCK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
    variables:
      damage: 1
      message: "Hello MythicMobs!"
      < ... >
```

## Variable Supported Types

The variables `attribute` only supports the following value types:

| Name         | Description                   | Example            |
|--------------|-------------------------------|--------------------|
| `int`        | Whole numbers                 | `damage: 5`        |
| `float`      | Decimal numbers               | `range: 3.5`       |
| `string`     | Text values (quoted if needed)| `message: "Hello!"`|

!!! caution
    Boolean, lists, or complex types are **not supported**. All values must be simple types and compatible with MythicMobs skill placeholders.

---

!!! note
    - Variables are accessed inside your skill using `<skill.var.variable_name>` format.
    - Use `"quotes"` for string values that include spaces or special characters.
