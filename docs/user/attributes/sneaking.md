The `sneaking` attribute checks whether the player is sneaking **before** executing the skill.

- If this attribute is **not set**, sneaking is ignored.
- If set to `true`, the skill will **only trigger when the player is sneaking**.
- If set to `false`, the skill will **only trigger when the player is not sneaking**.

!!! warning
    Make sure the value is correctly written as `true` or `false` (lowercase, no quotes).

---

# Example:
```yaml
Abilities:
- skill: SummonSkeleton
  activator: LEFT_CLICK
  sneaking: fale # Only triggers when the player is NOT sneaking
```