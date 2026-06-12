## Attributes

| Attribute | Aliases | Description                                                                                                       | Default |
|-----------|---------|-------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `type`    | `t`     |                                                                                                                   | `ARROW` |
	
## Example

```yaml
Skills:
- crossbowprojectile{t=arrow} @self
```

## Aliases
- addcrossbowprojectileitem