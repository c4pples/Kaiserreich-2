# Kaiserreich 2

Kaiserreich 2 is a total-conversion continuation of Kaiserreich for Hearts of Iron IV, set during the buildup to and outbreak of a hypothetical Third Weltkrieg.

This project treats Kaiserreich as historical canon and reference material. Its starting premise is not a replacement for KR, but a curated continuation: the Second Weltkrieg has ended, the old victors have failed to secure a stable peace, and the next global crisis grows from unresolved postwar settlements, ideological revanchism, and overstretched empires.

## Design Pillars

- Preserve Kaiserreich country characterization, ideological texture, and event-writing tone.
- Extend the setting through believable geopolitical evolution rather than sudden genre shifts.
- Keep the post-2WK settlement documented, modular, and easy to override for alternate start variants.
- Build faction and ideology systems around competing security needs, not simple good-versus-evil blocs.
- Prioritize long-term replayability by making secondary powers meaningful participants in crisis escalation.

## Documentation Map

- [Canon Assumptions](docs/canon_assumptions.md)
- [Postwar Timeline](docs/postwar_timeline.md)
- [Factions and Ideological Blocs](docs/factions_and_blocs.md)
- [Ideology Framework](docs/ideology_framework.md)
- [Revived Nationalism](docs/revived_nationalism.md)
- [Postwar Crisis System](docs/postwar_crisis_system.md)
- [Third Weltkrieg Outbreak](docs/third_weltkrieg_outbreak.md)
- [United States Fragmentation](docs/united_states_fragmentation.md)
- [Postwar Border Changes](docs/postwar_border_changes.md)
- [Country and Tag Plan](docs/country_tag_plan.md)
- [Canon Paths and Characters](docs/canon_paths_and_characters.md)
- [Kaiserreich Legacy Hooks](docs/kaiserreich_legacy_hooks.md)
- [Global Balance of Power](docs/global_balance_of_power.md)
- [Writing and Continuity Guide](docs/writing_continuity_guide.md)

## Source Reference

The official Kaiserreich HOI4 repository is used as the starting reference for mod structure, tags, localisation style, country files, events, focus-tree patterns, scripted effects, scripted triggers, national spirits, history files, state ownership, and canon tone:

- https://github.com/Kaiserreich/Kaiserreich-HOI4

The repository layout confirmed there should be compatibility with standard HOI4 mod organization, including `common`, `events`, `history`, `localisation`, `interface`, `map`, `gfx`, and test-support folders.

When implementing Kaiserreich 2, prefer adapting existing Kaiserreich structures and naming conventions over creating incompatible replacements. Any direct imported content should be tracked so later changes can distinguish original Kaiserreich material from Kaiserreich 2 continuation work.
