Changes the **custom model data** of an item in a specific slot.  
This is commonly used in resource pack-based plugins (like ItemsAdder, Oraxen, or Nexo) to change the appearance of an item.

!!! note
    Support for setting model data from other plugins is still under development. This feature may be available in future updates, but for now it only works exactly as vanilla `CustomModelData`.

## Attributes

| Attribute | Aliases | Description                                                                                                       | Default |
|-----------|---------|-------------------------------------------------------------------------------------------------------------------|---------|
| `slot`    | `s`     | The equipment slot where the item is located. See [EquipmentSlot](../../enum/equipment-slot.md) for valid values. | `HAND`  |
| `model`   | `m`     | The CustomModelData value to apply to the item.                                                                   | `0`     |

## Example

```yaml
Skills:
- setcustommodeldataitem{s=HAND;m=1001} @self
```

## Aliasses

- itemcaster:setcustommodeldataitem"
- itemcaster:setmodeldataitem"
- itemcaster:modeldataitem"
- setmodeldataitem"
- modeldataitem"