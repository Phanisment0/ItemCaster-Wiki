!!! note
    If you have plugin like `AuraSkills` or other plugin that has mana and supported in ItemCaster. this mechanic will be enabled

This check if the player max mana is less, more, or equals.

## Attributes

| Attribute | Aliases | Description       | Default |
|-----------|---------|-------------------|---------|
| `amount`  | `a`     | Range of max mana | `>1.0`  |

## Example
```yaml
Conditions:
- maxmana{a=>20} true
```

## Aliases
- itemcaster:maxmana