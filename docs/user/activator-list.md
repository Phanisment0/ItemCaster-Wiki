---
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

| Name                             | Description                                                                                                                                    |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| `LEFT_CLICK`                     | Triggered when the player hand is swing.                                                                                                       |
| `RIGHT_CLICK`                    | Triggered when the player right-clicks (air or block).                                                                                         |
| `INTERACT_ENTITY`                | Triggered when the player interacts with an entity.                                                                                            |
| `DROP`                           | Triggered when the player drops the item.                                                                                                      |
| `PICKUP`                         | Triggered when the player picks up the item.                                                                                                   |
| `PICKUP_EXP`                     | Triggered when the player picks up the xp.                                                                                                     |
| `DAMAGED`                        | Triggered when the player takes damage.                                                                                                        |
| `DAMAGED_BY_BLOCK_EXPLOSION`     | Triggered when the player damaged by block explosion.                                                                                          |
| `DAMAGED_BY_CAMPFIRE`            | Triggered when the player damaged by campfire.                                                                                                 |
| `DAMAGED_BY_CONTACT`             | Triggered when the player damaged by contact.                                                                                                  |
| `DAMAGED_BY_CRAMMING`            | Triggered when the player damaged by cramming.                                                                                                 |
| `DAMAGED_BY_CUSTOM`              | Triggered when the player damaged by custom.                                                                                                   |
| `DAMAGED_BY_DRAGON_BREATH`       | Triggered when the player damaged by dragon breath.                                                                                            |
| `DAMAGED_BY_DROWNING`            | Triggered when the player damaged by drowning.                                                                                                 |
| `DAMAGED_BY_ENTITY_ATTACK`       | Triggered when the player damaged by entity attack.                                                                                            |
| `DAMAGED_BY_ENTITY_EXPLOSION`    | Triggered when the player damaged by entity explosion.                                                                                         |
| `DAMAGED_BY_ENTITY_SWEEP_ATTACK` | Triggered when the player damaged by sweep attack.                                                                                             |
| `DAMAGED_BY_FALL`                | Triggered when the player damaged by fall.                                                                                                     |
| `DAMAGED_BY_FALLING_BLOCK`       | Triggered when the player damaged by falling block.                                                                                            |
| `DAMAGED_BY_FIRE`                | Triggered when the player damaged by fire.                                                                                                     |
| `DAMAGED_BY_FIRE_TICK`           | Triggered when the player damaged by fire tick.                                                                                                |
| `DAMAGED_BY_FLY_INTO_WALL`       | Triggered when the player damaged by fly into wall.                                                                                            |
| `DAMAGED_BY_FREEZE`              | Triggered when the player damaged by freeze.                                                                                                   |
| `DAMAGED_BY_HOT_FLOOR`           | Triggered when the player damaged by hot floor.                                                                                                |
| `DAMAGED_BY_KILL`                | Triggered when the player damaged by kill.                                                                                                     |
| `DAMAGED_BY_LAVA`                | Triggered when the player damaged by lava.                                                                                                     |
| `DAMAGED_BY_LIGHTNING`           | Triggered when the player damaged by lightning.                                                                                                |
| `DAMAGED_BY_MAGIC`               | Triggered when the player damaged by magic.                                                                                                    |
| `DAMAGED_BY_POISON`              | Triggered when the player damaged by poison.                                                                                                   |
| `DAMAGED_BY_PROJECTILE`          | Triggered when the player damaged by projectile.                                                                                               |
| `DAMAGED_BY_SONIC_BOOM`          | Triggered when the player damaged by sonic boom.                                                                                               |
| `DAMAGED_BY_STARVATION`          | Triggered when the player damaged by starvation.                                                                                               |
| `DAMAGED_BY_SUFFOCATION`         | Triggered when the player damaged by suffocation.                                                                                              |
| `DAMAGED_BY_SUICIDE`             | Triggered when the player damaged by suicide.                                                                                                  |
| `DAMAGED_BY_THORNS`              | Triggered when the player damaged by thorns.                                                                                                   |
| `DAMAGED_BY_VOID`                | Triggered when the player damaged by void.                                                                                                     |
| `DAMAGED_BY_WITHER`              | Triggered when the player damaged by wither.                                                                                                   |
| `DAMAGED_BY_WORLD_BORDER`        | Triggered when the player damaged by world border.                                                                                             |
| `ATTACK`                         | Triggered when the player attacks an entity.                                                                                                   |
| `TOGGLE_SNEAK`                   | Triggered when the player toggles sneaking (on/off).                                                                                           |
| `SNEAK`                          | Triggered when the player starts sneaking.                                                                                                     |
| `UNSNEAK`                        | Triggered when the player stops sneaking.                                                                                                      |
| `SHIELD_DISABLED`                |                                                                                                                                                |
| `STOP_USE_ITEM`                  |                                                                                                                                                |
| `CONSUME`                        | Triggered when the item is consumed (e.g., food or potion).                                                                                    |
| `BOW_SHOOT`                      | Triggered when the player shoots a bow.                                                                                                        |
| `DEATH`                          | Triggered when the player dies.                                                                                                                |
| `LOGIN`                          | Triggered when the player logs in.                                                                                                             |
| `QUIT`                           | Triggered when the player quits the game.                                                                                                      |
| `CHANGE_SLOT`                    | Triggered when the player changes the held item slot.                                                                                          |
| `CHANGE_WORLD`                   | Triggered when the player change dimension/world.                                                                                              |
| `ITEM_BREAK`                     | Triggered when the item breaks due to durability.                                                                                              |
| `FISHING`                        | Triggered when the player uses a fishing rod.                                                                                                  |
| `FISH_BITE`                      |                                                                                                                                                |
| `FISH_CAUGHT_ENTITY`             |                                                                                                                                                |
| `FISH_CAUGHT_FISH`               |                                                                                                                                                |
| `FISH_FAILED_ATTEMPT`            |                                                                                                                                                |
| `FISH_FISHING`                   |                                                                                                                                                |
| `FISH_IN_GROUND`                 |                                                                                                                                                |
| `FISH_REEL_IN`                   |                                                                                                                                                |
| `TOGGLE_SPRINT`                  | Triggered when the player toggles sprinting (on/off).                                                                                          |
| `SPRINT`                         | Triggered when the player starts sprinting.                                                                                                    |
| `UNSPRINT`                       | Triggered when the player stops sprinting.                                                                                                     |
| `BLOCK_PLACE`                    | Triggered when the player places a block.                                                                                                      |
| `BLOCK_BREAK`                    | Triggered when the player breaks a block.                                                                                                      |
| `BLOCK_DAMAGED`                  | Triggered when the player starts damaging a block.                                                                                             |
| `BLOCK_STOP_DAMAGED`             | Triggered when the player stops damaging a block.                                                                                              |
| `ARMOR_CHANGE`                   |                                                                                                                                                |
| `ELYRA_BOOST`                    |                                                                                                                                                |
| `TELEPORT`                       | Triggered when the player teleports.                                                                                                           |
| `TELEPORTED_BY_CHORUS_FRUIT`     |                                                                                                                                                |
| `TELEPORTED_BY_COMMAND`          |                                                                                                                                                |
| `TELEPORTED_BY_DISMOUNT`         |                                                                                                                                                |
| `TELEPORTED_BY_END_GATEWAY`      |                                                                                                                                                |
| `TELEPORTED_BY_END_PORTAL`       |                                                                                                                                                |
| `TELEPORTED_BY_ENDER_PEARL`      |                                                                                                                                                |
| `TELEPORTED_BY_EXIT_BED`         |                                                                                                                                                |
| `TELEPORTED_BY_NETHER_PORTAL`    |                                                                                                                                                |
| `TELEPORTED_BY_PLUGIN`           |                                                                                                                                                |
| `TELEPORTED_BY_SPECTATE`         |                                                                                                                                                |
| `TELEPORTED_BY_UNKNOWN`          |                                                                                                                                                |
| `CHANGE_WORLD`                   |                                                                                                                                                |
| `TICK`                           | Triggered every tick while the item is in hand.                                                                                                |
| `SIGNAL`                         | Triggered by signal form mechanic [`signal`](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/skills/mechanics/signal) in MythicMobs. |
| `CHANGE_SLOT_0`                  | Triggered when the player hotbar is moved to 0                                                                                                 |
| `CHANGE_SLOT_1`                  | Triggered when the player hotbar is moved to 1                                                                                                 |
| `CHANGE_SLOT_2`                  | Triggered when the player hotbar is moved to 2                                                                                                 |
| `CHANGE_SLOT_3`                  | Triggered when the player hotbar is moved to 3                                                                                                 |
| `CHANGE_SLOT_4`                  | Triggered when the player hotbar is moved to 4                                                                                                 |
| `CHANGE_SLOT_5`                  | Triggered when the player hotbar is moved to 5                                                                                                 |
| `CHANGE_SLOT_6`                  | Triggered when the player hotbar is moved to 6                                                                                                 |
| `CHANGE_SLOT_7`                  | Triggered when the player hotbar is moved to 7                                                                                                 |
| `CHANGE_SLOT_8`                  | Triggered when the player hotbar is moved to 8                                                                                                 |
| `CHANGE_SLOT_9`                  | Triggered when the player hotbar is moved to 9                                                                                                 |
