# Canon Paths and Characters

This is Pass 0 for determining who won, who lost, who survived, and who leads the major countries in the Kaiserreich 2 default timeline.

It should be verified against the Kaiserreich GitHub repository before implementation. Use KR country history files, character definitions, portraits, events, and focus trees as the source of truth for exact names, traits, and localisation keys. This document defines the continuation logic.

## Character Status Categories

- Winner: gained office, legitimacy, or strategic influence from the Second Weltkrieg settlement.
- Loser: defeated, exiled, imprisoned, politically discredited, or forced underground.
- Survivor: remains relevant but damaged, constrained, old, or dependent on others.
- Martyr: dead by 1950 and politically useful as memory or propaganda.
- Successor Needed: KR-era leader is too old, dead, displaced, or unsuitable for 1950 gameplay.
- Verify in KR: do not implement without checking current KR files.

## Global Canon Path Summary

| Country or Region | Default KR2 Path | 1950 Ruling Situation | Winner/Loser Logic |
| --- | --- | --- | --- |
| Germany | Reichspakt victory, no clean expansion | Constitutional empire under Kaiser Wilhelm III or equivalent successor | Germany wins control but inherits debt, dependence, and permanent mobilization |
| France | Commune defeated, Republic restored | Restored French Republic in Paris | Entente exiles win return; syndicalists lose the state but survive underground |
| Britain | Union defeated, monarchy restored | United Kingdom restored under Edward VIII or successor | Exiles win symbolically; Britain remains poor, divided, and dependent |
| Russia | Failed to break Germany, remains revisionist | Path-dependent anti-German state, likely nationalist or authoritarian | Russia loses the 2WK objective but wins the role of main challenger |
| United States | No claimant reunifies America | Fragmented successor states under armistice | All claimants are partial survivors; no true winner yet |
| Japan | Exploits European exhaustion | Imperial great power and Co-Prosperity leader | Strategic survivor and opportunistic winner |
| Ukraine | Reichspakt client under stress | German-aligned but nationalist pressure rising | Initial loser under German extraction; possible spark of 3WK |
| Poland | Reichspakt buffer under sovereignty pressure | German-aligned or treaty-bound | Survivor with strong nationalist resentment |
| White Ruthenia/Belarus | Exposed Reichspakt frontier | German-protected, legitimacy weak | Survivor, likely loyalist unless crisis breaks it |
| Italy | Socialist Italy defeated | Restored or federated Italian settlement | Anti-socialist forces win; unification remains unstable |
| Canada | Entente wartime pillar | Still powerful, but Britain has returned | Winner of exile struggle, loser of imperial centrality |
| National France/North Africa | Returns to Paris but destabilizes empire | Metropole restored; North Africa resentful | Wins return, loses colonial certainty |

## Locked Default Canon

These decisions are the default Kaiserreich 2 canon unless later overridden by a documented start rule.

### Second Weltkrieg

- Germany and the Reichspakt defeat the Third Internationale in Western Europe.
- The Entente participates decisively but returns through coalition victory, not independent triumph.
- Russia intervenes or supports the anti-German war effort but fails to break the eastern settlement.
- Japan exploits the war but does not become uncontested master of Asia.
- The United States remains fragmented and does not decide the war.

### Germany

- Germany remains a constitutional empire.
- Wilhelm II is dead or retired as a symbolic elder by 1950.
- Wilhelm III is the default Kaiser.
- Germany's domestic path is a wartime Burgfrieden that hardens into security constitutionalism: parliamentary life survives, but military, bureaucratic, and economic emergency powers are stronger than before.
- Germany does not annex France or Britain.

### France

- National France returns to Paris.
- The Commune of France is defeated as a state.
- Petain is not the long-term active leader in 1950.
- A restoration republic governs, with de Gaulle and other army-republican figures rising.
- France begins constrained by German treaty limits and divided between cooperation, sovereignty politics, and revanchism.

### Britain

- The Union of Britain is defeated.
- The United Kingdom is restored.
- Edward VIII remains the default monarch unless verification suggests a better KR-consistent succession.
- Britain is governed by a post-restoration cabinet, not personal royal rule.
- Labor compromise remains unavoidable; the revolutionary period cannot simply be erased.

### Russia

- Savinkovite or nationalist-authoritarian Russia is the default path.
- Russia loses the immediate Second Weltkrieg objective but survives as the main continental challenger.
- Savinkov is either aging ruler, founder above politics, or recently dead ideological martyr depending on implementation needs.
- The dominant Russian current by 1950 is National Maximalist: revenge, mobilization, and civilizational recovery against Germany.

### United States

- No American claimant reunifies the continent.
- The Federal Republic, Combined Syndicates remnant, American Union/National State, Pacific States, and contested interior all survive.
- Jack Reed and Huey Long may survive as burdened founders, but neither is a national victor.
- America is a campaign space, not a starting superpower.

### Italy

- Socialist Italy is defeated.
- The peninsula is not fully settled.
- A restored or federated anti-socialist order exists, but regional autonomy, monarchy, republicanism, and nationalist leagues remain unresolved.

### Eastern Europe

- Ukraine, Poland, White Ruthenia/Belarus, Lithuania, and the Baltic space remain in or around the Reichspakt system.
- They are not happy puppets. They are protected, indebted, militarized, and increasingly nationalist.
- Ukraine is the default spark of the Mitteleuropa Crisis.

### Austria-Hungary / Danubia

- The Danubian order survives in some federal or imperial form.
- It is a German partner, not a German puppet.
- Its role is to fear both Russian-backed Slavic revision and German absorption.

### Japan and China

- Japan remains imperial and Co-Prosperity focused.
- Hirohito remains head of state.
- Japan uses anti-European nationalism while struggling with client nationalism.
- China is not fully unified by default; it remains a major variable with Japanese pressure and rival governments.

### Mongolia

- The Ungern-Sternberg legacy should survive in some form, but by 1950 Roman von Ungern-Sternberg himself is likely dead, mythologized, or politically displaced.
- Mongolia should retain strange White Russian, Buddhist-monarchist, pan-Mongol, and steppe-military echoes as a deliberate KR legacy hook.

### Colonies and Mandates

- European empires are restored on paper more than in reality.
- National Populist, anarchist, syndicalist, and anti-colonial movements grow through the Postwar Reckoning.
- Colonies should not be passive manpower pools.

## Germany

Default path: victorious but strained constitutional empire.

Likely 1950 leader:

- Kaiser Wilhelm III, if Wilhelm II dies during or shortly after the Second Weltkrieg.

Status:

- Wilhelm II: Martyr or retired imperial symbol. By 1950 he is too old to be active; likely dead during the war or immediate postwar years.
- Wilhelm III: Winner and burdened successor. He inherits victory, not stability.
- German military and economic technocrats: Winners. They become essential to emergency management.
- Liberal parliamentarians: Survivors. They still exist but operate under security pressure.
- Hardline pan-German and security factions: Rising winners after the Postwar Reckoning.

Canon logic:

Germany should not feel like a triumphant dictatorship. It should feel like an empire whose institutions survived by accepting more military, financial, and bureaucratic emergency power than anyone wants to admit.

Verify in KR:

- current German leader roster,
- imperial family character entries,
- Schleicher, DU, SWR, and other Germany path figures if used as party leaders or elder statesmen.

## France

Default path: Commune defeated; French Republic restored from exile.

Likely 1950 leader:

- A post-exile republican or military-conservative government in Paris.
- Philippe Petain should not be the long-term active leader by 1950 except as a dying symbol, retired marshal, or recently deceased national figure.

Status:

- Philippe Petain: Survivor to Martyr. Useful as a symbol of return, but too old for long-term gameplay leadership.
- Charles de Gaulle: Likely Winner or rising successor. Strong candidate for army reform, national restoration, or anti-German sovereignty politics.
- Francois de La Rocque: Possible Winner if conservative republican or patriotic league politics dominate.
- Restored civilian republicans: Survivors. They return but are constrained by army, debt, and German treaty limits.
- Commune leadership: Losers. They are dead, imprisoned, exiled, or underground.
- French syndicalist militants: Losers as a state; Survivors as cells, unions, exiles, and resistance memory.
- French National Populists: Rising winners if humiliation and treaty limits dominate politics.

Canon logic:

France wins Paris back but not full freedom. The central French drama is whether restoration produces reconciliation, revanchism, German-aligned caution, or authoritarian national revival.

Verify in KR:

- National France leader list,
- Commune leader list,
- available French generals and political advisors.

## Britain

Default path: Union of Britain defeated; United Kingdom restored.

Likely 1950 leader:

- Edward VIII remains plausible if the monarchy survives exile and restoration.
- Government should be run by a post-restoration cabinet rather than the monarch personally.

Status:

- Edward VIII: Winner but constrained. Symbol of return, not a free hand.
- Canadian exile leadership: Winners turned awkward survivors. Their purpose changes once Britain returns.
- Union of Britain leadership: Losers. Totalists, syndicalists, and autonomists split into trials, exile, prison, or underground.
- Oswald Mosley: Major loser if Totalist UoB path was not canon; possible imprisoned, exiled, or clandestine symbol if he rose during the war.
- British labor moderates: Survivors. They may be necessary to prevent permanent unrest.
- British imperial diehards: Winners in rhetoric, constrained in practice.

Canon logic:

Britain returns as a state, not as the effortless center of the world. Restoration politics should be about monarchy, labor settlement, imperial exhaustion, and dependence on Canada and continental security.

Verify in KR:

- Union of Britain path figures,
- Canadian monarchy and exile cabinet characters,
- British restoration leader options.

## Russia

Default path: failed anti-German revision, still independent and dangerous.

Recommended canon path:

- Russia begins under a nationalist-authoritarian or national maximalist successor to the 1936 revisionist project.
- Savinkov is plausible as the ideological architect or aging ruler if his path is canon, but by 1950 succession pressure should be central.

Status:

- Boris Savinkov: Winner if his movement dominates Russia, but aging and politically dangerous. Could be active leader, Vozhd-like elder, or recently dead founder depending on desired tone.
- Liberal constitutionalists: Losers or constrained survivors. Germany's second victory discredits accommodation.
- Monarchists: Survivors or coalition partners. Useful if Russia frames revision through dynasty and Orthodoxy.
- Military modernizers: Winners. Any Russian path needs them.
- National Maximalists: Rising winners. Germany's second victory proves their argument.
- Left revolutionaries: Marginal survivors unless folded into Revolutionary Patriotism.

Canon logic:

Russia should not feel defeated into moderation. It should feel like the only great power whose whole politics now revolves around proving the German order can be broken.

Verify in KR:

- Russian post-Kerensky leader roster,
- Savinkov path characters,
- monarchist, military, and republican alternatives.

## Fragmented United States

Default path: no reunification.

Recommended canon situation:

- The Second American Civil War ended through armistice and exhaustion.
- Every major claimant has a founding myth, but no claimant has won.

### Federal Republic

Likely leaders:

- A constitutional continuity president or emergency national government.
- Quentin Roosevelt or another KR federal/PSA-compatible republican figure may be useful depending on which faction holds Washington.

Status:

- Federal constitutionalists: Survivors, not winners.
- Old two-party establishment: Losers unless rebuilt into a unity government.
- Emergency military figures: Survivors with dangerous prestige.

### Combined Syndicates Remnant

Likely leaders:

- Jack Reed may still be alive in 1950, but should be exhausted, aging, ill, retired, or contested if used.
- A successor generation should exist: syndicalist unionists, totalist organizers, anarchist federation leaders, democratic socialists.

Status:

- Jack Reed: Survivor or Martyr. If alive, he is the revolution's burdened founder rather than a fresh insurgent.
- Syndicalist union leadership: Survivors.
- Totalist cadres: Rising challengers.
- Anarchist networks: Rising local power in crisis zones.

### American Union/National State

Likely leaders:

- Huey Long can plausibly still be alive in 1950 if he survived the civil war, but his regime should face succession, corruption, and ideological hardening.

Status:

- Huey Long: Partial winner if his state survives; not a national winner.
- Business populists, veterans' leagues, clerical networks, and National Populists: Rising winners.
- Old federal elites: Losers in Union territory.

### Pacific States

Likely leaders:

- A constitutional-technocratic western government, possibly using KR PSA figures after verification.

Status:

- Pacific constitutionalists: Survivors.
- Naval and intelligence planners: Winners inside the state.
- Japanese-facing security hawks: Rising winners.

Canon logic:

America should be full of survivors and almost no winners. That is what makes reunification compelling.

Verify in KR:

- current 2ACW leader roster,
- CSA, AUS, USA, PSA, New England, and MacArthur path characters,
- who can plausibly survive to 1950.

## Japan

Default path: imperial great power survives and expands influence.

Likely 1950 leader:

- Emperor Hirohito remains head of state.
- Government direction should be military-influenced, conservative, and Co-Prosperity focused.

Status:

- Hirohito: Winner as imperial symbol.
- Japanese Army and Navy factions: Winners but internally divided.
- Civilian party cabinets: Survivors under pressure.
- Pan-Asian ideologues: Winners in propaganda, dangerous in client management.
- Client nationalists: Rising threats.

Canon logic:

Japan is a winner of European exhaustion, not a stable liberator. It sponsors nationalism abroad while fearing it inside its own sphere.

Verify in KR:

- Japan political path figures,
- Fengtian and Chinese client characters,
- Co-Prosperity related advisors.

## Ukraine

Default path: Reichspakt client and likely spark of the Mitteleuropa Crisis.

Likely 1950 leader:

- A Hetmanate, conservative republic, or German-aligned government with strong nationalist opposition.

Status:

- German-aligned elites: Survivors.
- Ukrainian army nationalists: Rising winners.
- Agrarian and land-reform movements: Crisis actors.
- Russian-backed factions: Covert challengers.
- Syndicalist labor undergrounds: Secondary accelerants.

Canon logic:

Ukraine should be the place where German economic need, national sovereignty, grain politics, army loyalty, and Russian intervention collide.

Verify in KR:

- Ukraine path leaders,
- Hetmanate figures,
- republican, socialist, and nationalist alternatives.

## Poland

Default path: Reichspakt-aligned buffer with unresolved sovereignty.

Likely 1950 leader:

- A monarchy, conservative government, or German-aligned constitutional regime with strong nationalist opposition.

Status:

- German-backed monarchists/conservatives: Survivors.
- Polish nationalists and army factions: Rising winners.
- Pro-Russian elements: Tactical minority, not natural majority.
- Socialists and syndicalists: Underground or marginal unless crisis deepens.

Canon logic:

Poland should not be automatically pro-Russian just because it resents Germany. Its politics are a three-way fear: Germany, Russia, and national humiliation.

Verify in KR:

- Polish royal candidates,
- nationalist and military figures,
- Reichspakt path characters.

## White Ruthenia / Belarus

Default path: exposed Reichspakt frontier.

Likely 1950 leader:

- German-protected conservative or military government.

Status:

- Loyalist state elites: Survivors.
- National Populist or native nationalist currents: Rising pressure.
- Russian-backed unionists: Covert challengers.

Canon logic:

Belarus/White Ruthenia is a loyalty test. It might side with Germany because Russia is terrifying, not because German rule is loved.

Verify in KR:

- current tag name and leader roster,
- local nationalist and German-aligned figures.

## Canada

Default path: Entente pillar whose purpose changes after British restoration.

Likely 1950 leader:

- Canadian parliamentary government under the restored imperial monarchy.

Status:

- Canadian exile establishment: Winners of the return, losers of centrality.
- Canadian national politicians: Rising winners, especially those asking what Canada gained.
- Imperial loyalists: Survivors.
- Anti-war and labor movements: Re-emerge after victory.

Canon logic:

Canada won the old Entente dream and then discovered that victory makes it less central.

Verify in KR:

- Canada leader roster,
- monarchy/exile cabinet characters,
- post-restoration event chains if present.

## Italy

Default path: Socialist Italy defeated; peninsula unsettled.

Likely 1950 leader:

- A restored monarchy, federation, or military caretaker depending on map choice.

Status:

- Socialist Italian leadership: Losers as rulers; some underground.
- Italian monarchists and republicans: Conditional winners.
- Nationalist veterans and anti-socialist leagues: Rising winners.
- Regional autonomists: Survivors.

Canon logic:

Italy should not be a solved country. The anti-socialist side wins the war but not the national question.

Verify in KR:

- Socialist Republic of Italy characters,
- Italian Republic/Federation/Two Sicilies/Sardinia leader pools.

## Character Implementation Rules

- Do not keep very old KR leaders in active office just because they are famous. Use them as dead founders, retired symbols, regents, field marshals, or faction patrons when appropriate.
- Preserve major KR personalities as memory whenever possible. A dead leader can still shape national spirits, party names, laws, trials, statues, and propaganda.
- Use successor generations to show that this is a new era, not 1936 with different borders.
- Every major ideology should have living organizers, not only abstract popularity.
- Character deaths should be politically meaningful, especially for Wilhelm II, Petain, Reed, Savinkov, and major syndicalist leaders.
- A country can be led by a less famous bureaucrat if the real drama is between factions, veterans, radicals, and foreign patrons.

## Immediate Verification Tasks

When the KR repository is imported or accessible locally, verify:

- `history/countries` for 1936 ruling leaders and parties,
- `common/characters` for available named characters and portraits,
- `events` for path-specific deaths, retirements, and exiles,
- `common/national_focus` for canonical path implications,
- `localisation` for exact party and leader names,
- portrait availability for aged or successor leaders.
