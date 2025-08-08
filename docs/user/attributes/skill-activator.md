These two attributes are **required** in every ability entry. If either one is missing, the ability will **not be executed**.

| Attribute   | Description |
|-------------|-------------|
| `skill`     | The MythicMobs skill ID to be executed. |
| `activator` | The trigger event that activates the skill. [See all available activators here](../activator-list.md). |

---

## Example
```yaml
Example:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
```