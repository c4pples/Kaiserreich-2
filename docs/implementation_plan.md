# Implementation Plan

This document converts the design bible into a practical HOI4 mod build order.

## Milestone 1: KR2 Playable Shell

Goal: create a valid mod structure that can load in Hearts of Iron IV before large content is ported.

Deliverables:

- `descriptor.mod`
- standard HOI4 folders
- upstream reference policy
- ideology framework implementation
- initial localisation namespace
- first country history targets
- first global event namespace

Current status:

- documentation baseline exists,
- GitHub repository exists,
- empty HOI4 folder skeleton exists,
- implementation content has not yet been ported from Kaiserreich.

## Folder Skeleton

Required folders:

- `common`
- `common/ideologies`
- `common/country_tags`
- `common/national_focus`
- `common/ideas`
- `common/scripted_effects`
- `common/scripted_triggers`
- `common/decisions`
- `events`
- `history`
- `history/countries`
- `history/states`
- `localisation/english`
- `interface`
- `gfx`
- `map`

Empty folders are tracked with `.gitkeep` until real content exists.

## Build Order

### Step 1: Ideologies

Start with ideology definitions because country history, parties, events, and focus trees depend on them.

Tasks:

- import or adapt Kaiserreich ideology structure,
- split anarchism into its own ideology,
- preserve syndicalism and totalism,
- keep National Populism prominent,
- add localisation for ideology names and descriptions,
- verify compatibility with KR-style party popularity.

### Step 2: Core Tags

Create or adapt country tags for the first playable batch:

- Germany,
- Russia,
- French Republic,
- United Kingdom,
- Japan,
- Ukraine,
- Federal Republic,
- Combined Syndicates Remnant,
- American Union/National State,
- Pacific States.

Tasks:

- confirm tag IDs from Kaiserreich where possible,
- define any new tags needed for fragmented America,
- add `common/country_tags` entries,
- create placeholder history files,
- add basic party popularity and ruling ideology.

### Step 3: Global Systems

Implement the opening world systems as event and decision scaffolds.

Systems:

- Postwar Reckoning,
- Mitteleuropa Crisis,
- client revolt risk,
- bloc cohesion,
- revived nationalism pressure,
- syndicalist underground,
- anarchist local power,
- totalist cadre strength.

### Step 4: Character Verification

Use Kaiserreich files to confirm:

- living leaders,
- dead or retired founders,
- portraits,
- advisor availability,
- country leader traits,
- field marshal and general pools.

### Step 5: Map and History

Only after ideology and tag decisions are stable:

- adapt KR state ownership,
- restore France and Britain,
- fragment the United States,
- preserve the German eastern order,
- set Ukraine as the likely crisis spark,
- leave China and colonial mandates modular.

## Import Policy

Do not bulk-copy Kaiserreich blindly. Import deliberately:

- copy structure first,
- track copied files,
- annotate KR2-specific changes,
- keep direct KR imports separate from original KR2 documents when practical.

## First Commit Target

The first implementation commit after this scaffold should add:

- `common/ideologies/00_ideologies.txt`,
- `localisation/english/KR2_ideologies_l_english.yml`,
- placeholder global event namespace for the Postwar Reckoning.
