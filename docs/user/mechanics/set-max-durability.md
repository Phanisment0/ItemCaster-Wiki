## Attributes

| Attribute | Aliases | Description                                                                                                           | Default |
|-----------|---------|-----------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item will be placed. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `amount`  | `a`     |                                                                                                                       | `1`     |

## Example

```yaml
Skills:
- setmaxdurabilityitem{a=100} @self
```