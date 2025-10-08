The `sneaking` attribute checks whether the player is sneaking **before** executing the skill.

- If this attribute is **not set**, sneaking is ignored.
- If set to `true`, the skill will **only trigger when the player is sneaking**.
- If set to `false`, the skill will **only trigger when the player is not sneaking**.

---

# Example:
```yaml
Abilities:
- skill: SummonSkeleton
  activator: LEFT_CLICK
  sneaking: false # Only triggers when the player is NOT sneaking
```