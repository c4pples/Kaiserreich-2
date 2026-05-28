# Kaiserreich Legacy Hooks

Kaiserreich 2 should reward players who know Kaiserreich. The world has moved on, but old figures, strange paths, exiles, and ideological oddities should still leave fingerprints across the map.

These hooks should be subtle, useful, and occasionally playable. They should not freeze the world in 1936 nostalgia. A recognizable KR character can be:

- an aging ruler,
- a dead founder,
- an exile,
- a military advisor,
- a prisoner,
- a foreign volunteer,
- a memoirist,
- a hidden event chain,
- a portrait in a cabinet,
- the namesake of a national spirit,
- or the patron saint of an extremist faction.

## Design Rules

- Use KR characters where they plausibly survived to 1950.
- If a character is too old, make them a symbol, martyr, retired patron, or recently deceased founder.
- Preserve odd KR flavor, but age it through consequences.
- Do not make every cameo powerful. Some should be rumors, memoirs, statues, trials, or intelligence reports.
- Let old losers matter as myths. Defeated people often become more useful dead, exiled, or imprisoned than they were in office.
- Verify exact character availability against the KR GitHub files before implementation.

## High-Priority Legacy Hooks

### Mongolia and the White Russian Orbit

KR recognition:

- Roman von Ungern-Sternberg's Mongolia is one of Kaiserreich's most memorable oddities.
- The broader White Russian steppe orbit can connect Mongolia, Transamur memories, Russian exiles, Cossack remnants, and Japanese intelligence.

KR2 continuation:

- Ungern is likely dead, vanished, or mythologized by 1950.
- Mongolia can contain an "Ungernite" officer clique, a Buddhist-monarchist court faction, White Russian veterans, and pan-Mongol nationalists.
- Russia, Japan, and Chinese factions can all court or suppress these remnants.

Possible gameplay:

- hidden advisor: Last Men of the Asiatic Cavalry,
- national spirit: The Mad Baron's Shadow,
- event: The Regent's Bones,
- decision: Recruit White Russian Veterans,
- crisis: Pan-Mongol officers demand a raid into contested frontier territory.

### Savinkov's Russia

KR recognition:

- Savinkov is one of the defining Russian path figures.

KR2 continuation:

- If alive, he is aging and dangerous.
- If dead, his movement controls the language of Russian revenge.
- National Maximalists claim to be his heirs while arguing the next war requires an even more mobilized state.

Possible gameplay:

- succession struggle,
- Vozhd cult national spirit,
- security-state versus army-modernizer split,
- exiled Russian liberals using Savinkov's failures as propaganda.

### The Exiled Entente Returns

KR recognition:

- Canada, National France, Sand France, and the British royal exile are central KR experiences.

KR2 continuation:

- Their return should be full of awkward survivors.
- Canada must ask what victory cost.
- France and Britain must decide what to do with exile-era leaders who are too old, too colonial, or too compromised.

Possible gameplay:

- trials of collaborators and syndicalists,
- return of exile officers,
- colonial veterans demanding reward,
- Canadian resentment at losing imperial centrality.

### Defeated Syndicalist Leaders

KR recognition:

- Commune, Union of Britain, and Socialist Italy leaders should not simply disappear.

KR2 continuation:

- Some are executed or imprisoned.
- Some escape to the Combined Syndicates remnant, Mexico, South America, India, China, or colonial undergrounds.
- Some become martyrs whose portraits appear in illegal union halls.

Possible gameplay:

- foreign syndicalist advisor events,
- prison break chain,
- exile congress,
- totalist versus syndicalist split in the American CSA remnant,
- anarchists rejecting both old Commune bureaucracy and totalist discipline.

### Fragmented America Founders

KR recognition:

- Reed, Long, MacArthur, PSA leaders, New England figures, and federal constitutionalists are core KR characters.

KR2 continuation:

- No claimant wins.
- Founders are aging, dead, compromised, or trapped by the states they created.
- Successor generations should fight over what the civil war meant.

Possible gameplay:

- Reed's last speech or Reed memorial congress,
- Longist succession crisis,
- MacArthurist emergency-law legacy,
- Pacific constitutional convention,
- New England recognition crisis,
- veterans from every claimant crossing borders as mercenaries or ideologues.

### German Old Guard and New Technocrats

KR recognition:

- Germany's KR paths include parliamentary, military, and conservative blocs with strong personalities.

KR2 continuation:

- The old guard won the war but left the empire indebted.
- New technocrats, intelligence chiefs, and emergency planners now claim only they can keep the system alive.

Possible gameplay:

- retired war hero condemns emergency measures,
- Reichstag debt scandal,
- Mitteleuropa banker suicide or assassination,
- young officers demand command integration of clients,
- old liberal leaders try to save constitutionalism.

### Mittelafrika and Colonial Veterans

KR recognition:

- Mittelafrika is a central KR institution and a natural source of chaos.

KR2 continuation:

- Whether intact, reformed, or partially collapsed, it should leave officers, settlers, companies, African intermediaries, and insurgent networks across the continent.

Possible gameplay:

- German colonial officer appears as advisor in a successor mandate,
- African veterans organize nationalist leagues,
- company security forces become semi-independent,
- anti-colonial syndicalists and National Populists compete.

### Japan's Client Nationalists

KR recognition:

- Japan's Co-Prosperity politics and Chinese clients should remain recognizable.

KR2 continuation:

- Japan's old collaborators now have their own nationalist agendas.
- Some still need Tokyo. Others want independence from both Europe and Japan.

Possible gameplay:

- pan-Asian congress goes off-script,
- client army refuses Japanese command,
- Chinese officer trained by Japan defects,
- Japanese intelligence funds one nationalist group to suppress another.

## Cameo Categories

### Active Leaders

Use sparingly. Good for figures who are still plausible in 1950:

- Wilhelm III,
- Edward VIII,
- Hirohito,
- some American faction founders if not too old or discredited,
- younger military and political figures like de Gaulle.

### Elder Statesmen

Useful for famous older figures:

- Petain,
- old Canadian exile politicians,
- aging German path leaders,
- old Russian generals,
- surviving syndicalist founders.

### Martyrs and Founders

Best for figures whose death strengthens a movement:

- Wilhelm II,
- Jack Reed if deceased,
- Savinkov if deceased,
- major Commune or UoB leaders,
- slain American faction leaders.

### Exiles and Foreign Advisors

Best for fun KR continuity:

- defeated syndicalists in America or colonial movements,
- White Russian officers in Mongolia, China, or Japanese service,
- German colonial officers in African successor states,
- Entente intelligence figures in former revolutionary countries,
- American pilots, engineers, and veterans selling skills abroad.

### Prisoners and Trial Subjects

Excellent for event flavor:

- UoB ministers,
- Commune security officials,
- collaborationist officials,
- failed coup leaders,
- foreign agents caught during the Mitteleuropa Crisis.

## Implementation Ideas

Recommended national spirits:

- The Mad Baron's Shadow
- The Exiles Return
- Founders Without Victory
- The Vozhd's Testament
- The Old Marshal's Silence
- Veterans of the Weltkrieg and Civil War
- The Unfinished Revolution
- The Colonial Officer Corps

Recommended event types:

- obituary events,
- memoir publication events,
- hidden advisor discovery,
- exile congresses,
- intelligence reports,
- trial verdicts,
- statue removals or dedications,
- return of a foreign volunteer,
- rumors of a vanished leader.

## Immediate KR Verification Targets

When the KR GitHub repository is imported locally, search:

- `common/characters` for named leaders and portraits,
- `history/countries` for start leaders and party names,
- `events` for deaths, exiles, and path outcomes,
- `common/national_focus` for path-exclusive figures,
- `localisation` for exact names and titles.

Specific searches:

- Ungern-Sternberg,
- Wrangel,
- Savinkov,
- Reed,
- Long,
- MacArthur,
- Edward VIII,
- Petain,
- de Gaulle,
- Mosley,
- Wilhelm,
- Hirohito.
