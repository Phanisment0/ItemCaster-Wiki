# Conditions

## Aura Stats Level

### Attributes

| Attribute | Aliases | Description | Default    |
|-----------|---------|-------------|------------|
| `stats`   | `s`     | Stats type  | `STRENGTH` |
| `level`   | `l`     | Stats level | `>1`       |

### Example
```yaml
Conditions:
- aurastatslevel{l=>10} true
```

## Aura Skill Level

### Attributes

| Attribute | Aliases | Description | Default    |
|-----------|---------|-------------|------------|
| `skill`   | `s`     | Skill type  | `FIGHTING` |
| `level`   | `l`     | Skill level | `>1`       |

### Example
```yaml
Conditions:
- auraskilllevel{l=>10} true
```