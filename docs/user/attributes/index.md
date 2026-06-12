---
title: Attribute List
icon: material/cube
authors:
- phanisment
---

| Name                                | Type          | Description                                                                                         |
|-------------------------------------|---------------|-----------------------------------------------------------------------------------------------------|
| [skill](./skill-activator.md)       | `string`      | The ID of the MythicMobs skill to be executed.                                                      |
| [activator](./skill-activator.md)   | `string`      | The trigger event name. See [Activator List](../activator-list.md).                                 |
| [power](./power.md)                 | `float`       | Determine the power of the skill mechanic that uses power as a base of multiplier value (Optional)  |
| [cooldown](./cooldown.md)           | `double`      | Cooldown duration in seconds before reuse. (Optional)                                               |
| [sneaking](./sneaking.md)           | `boolean`     | If set, checks the player's sneaking state. (Optional)                                              |
| [show_cooldown](./show-cooldown.md) | `boolean`     | Show cooldown bar in action bar caster when activate the skill. (Optional)                          |
| [signal](./signal.md)               | `string`      | Used when signal is equals. Only used with `SIGNAL` activator. (Optional)                           |
| [variables](./variables.md)         | `object(map)` | Defines variables passed to the MythicMobs skill. Supports `string`, `int`, and `float`. (Optional) |

---

!!! note
    - All attributes are **optional** except `skill` and `activator`.
    - The plugin will ignore any malformed or incomplete ability entries.
    - You can include multiple abilities in one item using the `abilities` array.