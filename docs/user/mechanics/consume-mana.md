!!! note
    If you have plugin like `AuraSkills` or other plugin that has mana and supported in ItemCaster. this mechanic will be enabled

Consume mana of player.

## Attributes

| Attribute | Aliases | Description               | Default |
|-----------|---------|---------------------------|---------|
| `amount`  | `a`     | Amount mana to be consume | `1.0`   |

## Example
```yaml
Skills:
- consumemana{a=>10} true
```

## Aliases
- itemcaster:consumemana
- itemcaster:decreasemana
- decreasemana