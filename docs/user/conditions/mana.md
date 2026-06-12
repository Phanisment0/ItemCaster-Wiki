!!! note
    If you have plugin like `AuraSkills` or other plugin that has mana and supported in ItemCaster. this mechanic will be enabled

This check if the player mana is less, more, or equals.

## Attributes

| Attribute | Aliases | Description   | Default |
|-----------|---------|---------------|---------|
| `amount`  | `a`     | Range of mana | `>1.0`  |

## Example
```yaml
Conditions:
- mana{a=>10} true
```

## Aliases
- itemcaster:mana