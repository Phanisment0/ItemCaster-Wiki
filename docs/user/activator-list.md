---
date:
  created: 2025-08-4
  updated: 2025-08-7
authors:
- phanisment
---

This is list of Activator or you can say it Event to Trigger MythicMobs skill.

Configuration Example:
```yaml
Example_Item:
  Id: STICK
  Abilities:
  - skill: SummonSkeleton
    activator: LEFT_CLICK
```

NBT/Command Example:
```mcfunction 
give @s stick[minecraft:custom_data={
  ItemCaster: {
    abilities: [
      {
        skill: "SummonSkeleton",
        activator: "LEFT_CLICK"
      }
    ]
  }
}]
```

| Name                 | Description |
|----------------------|-------------|
| `LEFT_CLICK`         | Triggered when the player hand is swing. |
| `RIGHT_CLICK`        | Triggered when the player right-clicks (air or block). |
| `INTERACT_ENTITY`    | Triggered when the player interacts with an entity. |
| `DROP`               | Triggered when the player drops the item. |
| `PICKUP`             | Triggered when the player picks up the item. |
| `DAMAGED`            | Triggered when the player takes damage. |
| `ATTACK`             | Triggered when the player attacks an entity. |
| `TOGGLE_SNEAK`       | Triggered when the player toggles sneaking (on/off). |
| `SNEAK`              | Triggered when the player starts sneaking. |
| `UNSNEAK`            | Triggered when the player stops sneaking. |
| `CONSUME`            | Triggered when the item is consumed (e.g., food or potion). |
| `BOW_SHOOT`          | Triggered when the player shoots a bow. |
| `DEATH`              | Triggered when the player dies. |
| `LOGIN`              | Triggered when the player logs in. |
| `QUIT`               | Triggered when the player quits the game. |
| `CHANGE_SLOT`        | Triggered when the player changes the held item slot. |
| `ITEM_BREAK`         | Triggered when the item breaks due to durability. |
| `FISHING`            | Triggered when the player uses a fishing rod. |
| `TOGGLE_SPRINT`      | Triggered when the player toggles sprinting (on/off). |
| `SPRINT`             | Triggered when the player starts sprinting. |
| `UNSPRINT`           | Triggered when the player stops sprinting. |
| `BLOCK_PLACE`        | Triggered when the player places a block. |
| `BLOCK_BREAK`        | Triggered when the player breaks a block. |
| `BLOCK_DAMAGED`      | Triggered when the player starts damaging a block. |
| `BLOCK_STOP_DAMAGED` | Triggered when the player stops damaging a block. |
| `TELEPORT`           | Triggered when the player teleports. |
| `TICK`               | Triggered every tick while the item is in hand.  |
| `SIGNAL`             | Triggered by signal form mechanic [`signal`](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/skills/mechanics/signal) in MythicMobs. |
