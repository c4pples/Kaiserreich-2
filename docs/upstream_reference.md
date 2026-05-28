# Upstream Reference

Kaiserreich 2 uses the official Kaiserreich HOI4 repository as its primary structural and lore reference.

Upstream:

- https://github.com/Kaiserreich/Kaiserreich-HOI4

## What To Reuse

Prefer Kaiserreich source material for:

- country tags,
- state ownership patterns,
- leader and advisor names,
- portraits where appropriate,
- ideology structure,
- localisation style,
- event style,
- focus tree conventions,
- scripted effects and triggers,
- decision categories,
- national spirits,
- map structure,
- interface conventions.

## What To Change

Kaiserreich 2 should change content where the post-Second Weltkrieg timeline requires it:

- defeated Internationale states,
- restored Britain and France,
- fragmented United States,
- Reichspakt postwar order,
- Russian revisionism,
- Japan's postwar Pacific strategy,
- revived nationalism,
- Postwar Reckoning,
- Mitteleuropa Crisis,
- anarchism split from syndicalism.

## Tracking Rules

When importing from Kaiserreich:

- preserve filenames where it helps compatibility,
- note large direct imports in this document or a future import log,
- avoid rewriting KR systems without reason,
- keep KR2 original documentation under `docs`,
- add comments near major divergences when useful.

## Initial Verification Targets

Once the Kaiserreich source is available locally, inspect:

- `common/ideologies`
- `common/country_tags`
- `common/characters`
- `history/countries`
- `history/states`
- `events`
- `common/national_focus`
- `common/ideas`
- `common/scripted_effects`
- `common/scripted_triggers`
- `localisation/english`
