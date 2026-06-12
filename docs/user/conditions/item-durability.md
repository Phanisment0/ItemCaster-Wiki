## Attributes

| Attribute | Aliases | Description                                                                                                           | Default |
|-----------|---------|-----------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item will be placed. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `amount`  | `a`     |                                                                                                                       | `0`     |

## Example
```yaml
Conditions:
- itemdurability{a=>10} true
```