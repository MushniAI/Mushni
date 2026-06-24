# Character Consistency Prompt Patterns

Character consistency improves when stable details are written once and reused across prompts.

## Character Lock Prompt

```text
Use the following character details as stable continuity rules.
Do not change the character's name, age range, core appearance, personality, or relationship role unless explicitly instructed.

Character:
- Name:
- Role:
- Appearance:
- Clothing:
- Personality:
- Speaking style:
- Important relationships:
- Details to avoid changing:
```

## Scene Generation Prompt

```text
Create a scene using the character continuity rules below.

Scene goal:
[describe the scene goal]

Characters:
[paste character lock blocks]

Setting:
[location, time, mood]

Output format:
[story prose / comic panel list / image prompt / video shot list]

Continuity requirements:
- Keep character appearance stable.
- Keep relationships consistent.
- Do not introduce new major facts without marking them as optional.
- Flag any unclear detail before making assumptions.
```

## Revision Prompt

```text
Revise the output below while preserving all stable character details.

Revision goal:
[what should improve]

Do not change:
[list details that must remain stable]

Output to revise:
[paste draft]
```
