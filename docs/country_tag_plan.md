# Country and Tag Plan

This document translates the Kaiserreich 2 setting baseline into implementable starting tags. It is not yet a complete HOI4 `history/countries` map, but it defines the political logic each starting country should express.

## Tag Planning Rules

- Use the official Kaiserreich GitHub repository as the baseline for existing country tags, states, history files, localisation keys, ideologies, scripted effects, and event style.
- Prefer extending or adapting KR structures before inventing new replacements.
- Tags should represent playable political projects, not only map color.
- A tag's ruling ideology should describe its governing coalition, while national spirits can track underground radical currents.
- Faction membership, economic alignment, and ideological sympathy should be separate where possible.
- Avoid overusing puppets. Treaty limits, military missions, debts, basing rights, and customs unions often represent the postwar order better than direct subject status.
- Use National Populist parties and national spirits more aggressively in puppets, mandates, colonies, defeated states, and client regimes. The Third Weltkrieg era is driven by revived nationalism more than by open syndicalist bloc politics.
- Major uncertain Kaiserreich outcomes should be handled through start rules or alternate setup files.

## Core European Tags

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| German Empire | Defensive hegemon | Constitutional imperial, authoritarian democratic or social conservative | Reichspakt leader | Preserve the post-2WK order while managing debt, allies, veterans, and Russia |
| French Republic | Restored but constrained power | Conservative restorationist, authoritarian democratic, or social liberal path options | Entente core, treaty-bound to Germany | Rebuild sovereignty without triggering German intervention or syndicalist revival |
| United Kingdom | Restored island state | Conservative restorationist with social compromise pressure | Entente core | Reconcile monarchy, labor, empire, and dependence on Canada/Germany |
| Ireland | Armed neutral pressure point | Republican, conservative, or labor-democratic | Neutral, contested by Entente/Reichspakt/underground left | Maintain independence amid British restoration and Atlantic militarization |
| Italian Settlement | Unresolved peninsula | Restored monarchy, federation, republic, or military caretaker | Entente/Reichspakt-adjacent, not fully secure | Decide unification, anti-syndicalist justice, and regional autonomy |
| Belgium/Flanders-Wallonia | Western security hinge | German-influenced constitutional order | Reichspakt-aligned or treaty-neutral | Balance German security demands and Franco-British pressure |
| Netherlands | Commercial neutral under pressure | Liberal, conservative, or managed democracy | Neutral with German economic gravity | Preserve trade independence between Britain and Mitteleuropa |
| Spain | Exhausted ideological crossroads | Start-rule dependent | Neutral, Entente-leaning, Reichspakt-leaning, or revolutionary remnant | Civil-war memory, labor repression, and Mediterranean alignment |
| Portugal | Entente Atlantic partner | Conservative republic or authoritarian democratic | Entente-aligned | Protect empire and Atlantic routes while managing domestic stagnation |

## Reichspakt and Eastern Frontier

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Poland | Buffer state with legitimacy crisis | Monarchist, conservative, nationalist parliamentary, or National Populist opposition | Reichspakt member or protected ally | German security versus national sovereignty and Russian pressure |
| Lithuania | Baltic-Polish hinge | Conservative, royal-constitutional, or nationalist opposition | Reichspakt-aligned | Balance local nationalism, German influence, and border defense |
| Ukraine | Grain, industry, and eastern frontier | Hetmanate, conservative republic, nationalist coalition, or National Populist pressure | Reichspakt member | Land reform, army loyalty, Russian agitation, and German economic extraction |
| White Ruthenia/Belarus | Exposed frontier state | Conservative, military, nationalist, or National Populist underground | Reichspakt member | Survival between German protection and Russian irredentism |
| United Baltic Duchy or Baltic Federation | Northern fortress | German-Baltic conservative, federal compromise, or native nationalist opposition | Reichspakt member | Defend against Russia while containing local resentment |
| Finland | Northern anti-Russian state | Conservative, nationalist, or democratic | Reichspakt-leaning, possibly neutral | Choose between German guarantees and independent Nordic policy |
| Don-Kuban or Cossack Borderland | Optional buffer | Military frontier government | German-backed, Russian-claimed, or neutral | Raids, legitimacy, and Russian reintegration pressure |

## Danubia and Balkans

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Austria-Hungary or Danubian Federation | Conservative stabilizer | Federal imperial, reformist monarchy, or successor pact | Reichspakt partner, not subordinate | Resist German absorption while preventing Balkan escalation |
| Hungary | Internal or successor power | Conservative, nationalist, or authoritarian | Danubian-aligned or revisionist | Autonomy, minority borders, and relation to Vienna |
| Serbia | Revisionist Balkan actor | National democratic, royalist, military, or National Populist | Russian-leaning or neutral | Recover influence without triggering Danubian/German response |
| Romania | Oil and frontier power | Royal authoritarian, nationalist, conservative, or National Populist | Contested between Germany, Russia, and Balkan blocs | Oil security, Bessarabia, and regional leadership |
| Bulgaria | Treaty-weary survivor | Monarchist, military, or nationalist revanchist | Neutral, German-leaning, or opportunist | Manage territorial claims and avoid encirclement |
| Greece | Mediterranean hinge | Monarchist, republican, or military | Entente-leaning or neutral | Aegean security, monarchy question, and Balkan guarantees |
| Albania | Small-state pressure point | Clan, royal, or protectorate politics | Italian/Danubian/Entente contested | Survival through patronage and neutrality |

## Russia and Its Sphere

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Russia | Revisionist land power | Constitutional revisionist, monarchist, national maximalist, Eurasian statist, or revolutionary patriot | Moscow Accord leader | Break the German order without collapsing from overmobilization |
| Caucasus States | Mountain and oil frontier | Start-rule dependent | Russian, German, Ottoman, or neutral influence | Oil, minorities, military corridors, and great-power pressure |
| Central Asian States | Strategic depth and resource zone | Protectorates, republics, khanates, or Russian-aligned authorities | Russian sphere or contested | Modernization, autonomy, and Russian military access |
| Persia/Iran | Buffer and oil state | Monarchy, constitutionalist, or military | Neutral, Russian-leaning, German-leaning, or British-influenced | Avoid becoming the corridor war of the Third Weltkrieg |

## Fragmented America

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Federal Republic | Constitutional claimant | Social liberal, market liberal, social conservative, or emergency democratic | Entente-friendly but cautious | Restore legitimacy and decide whether reunification is worth another war |
| Combined Syndicates Remnant | Revolutionary industrial state | Syndicalist, totalist, anarchist, or democratic socialist split | Revolutionary, isolated, possible covert Russian ties | Survive encirclement and define the future of American socialism |
| American Union/National State | Populist-national claimant | National populist, paternal autocrat, or conservative populist | Anti-syndicalist, not automatically Entente | Reunify through force, bargaining, or ideological consolidation |
| Pacific States | Western constitutional-technocratic state | Market liberal, social liberal, authoritarian democratic, or military emergency | Japan-wary, externally courted | Balance Pacific defense, trade, and reunification ambitions |
| Interior Authorities | Contested corridor system | Local military, state governments, native authorities, or neutral commissions | Mixed and influence-driven | Control transport, food, refugees, and demilitarized zones |
| Canada | Entente survivor and North American stabilizer | Conservative, liberal, or imperial caretaker | Entente core | Manage Britain's return while preventing American spillover |
| Mexico | Regional opportunist | Revolutionary, nationalist, or institutional government | Neutral, anti-imperial, or claimant-backed | Exploit American weakness without provoking intervention |

## Asia-Pacific

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Japan | Pacific great power | Imperial, military-influenced, or conservative modernizing | Co-Prosperity leader | Secure resources and clients before America or Europe recovers |
| Fengtian/Manchurian Order | Japanese continental partner | Military, monarchist, or client republican | Co-Prosperity aligned | Balance Chinese legitimacy and Japanese control |
| Chinese National Government | Central unifier candidate | Start-rule dependent | Neutral, anti-Japanese, German-backed, or pragmatic | Unify China while resisting foreign domination |
| Southern Chinese Government | Rival Chinese project | Federalist, nationalist, socialist, or regional | Contested | Build legitimacy against both Japan and northern rivals |
| German East Asian Remnants | Treaty-port and naval network | Colonial administration or leased-zone authority | Reichspakt | Preserve German access without provoking Japan |
| Australasia | Pacific Entente outpost | Dominion democracy or emergency government | Entente | Defend sea lanes amid Japanese pressure and British weakness |
| India Successor States | Subcontinental great variable | Start-rule dependent | Entente, revolutionary, princely, or nationalist blocs | Decide whether India is unified, partitioned, or factionalized |

## Middle East and Africa

| Tag Concept | Start Role | Ruling Direction | Faction Posture | Starting Conflict |
| --- | --- | --- | --- | --- |
| Ottoman Empire or Turkish Republic | Regional order-holder or successor | Start-rule dependent | Neutral, German-leaning, or revisionist | Control straits, oil routes, minorities, and Arab periphery |
| Egypt | Canal and anti-colonial hinge | Monarchy, nationalist, military, or National Populist mass movement | Entente-contested, neutral, or anti-colonial | Suez control and British restoration pressure |
| Arabia | Decentralized strategic region | Monarchies, tribal coalitions, protectorates, or religious-nationalist leagues | Contested | Oil, pilgrimage legitimacy, and patronage competition |
| Mittelafrika or German African Successors | Colonial overstretch system | German colonial, mandate, successor administrations, or nationalist insurgencies | Reichspakt | Hold resources amid insurgency and administrative decay |
| National France/North African Settlement | Restored metropole's imperial problem | French colonial, autonomous, nationalist, or National Populist anti-colonial pressure | Entente | Reconcile return to Paris with North African legitimacy crisis |
| South Africa | Dominion and regional power | Democratic, nationalist, or segregationist state | Entente-leaning or neutral | Internal racial order, imperial ties, and African strategy |

## Ideology Implementation Priorities

Create or revise ideology definitions early enough that country plans can use them consistently.

Required ruling ideologies:

- social conservative,
- market liberal,
- social liberal,
- social democrat,
- syndicalist,
- anarchist,
- totalist,
- authoritarian democrat,
- paternal autocrat,
- national populist.

Recommended subcurrents through national spirits:

- Russian national maximalism,
- Eurasian statism,
- revolutionary patriotism,
- revived nationalism,
- National Populist client-state pressure,
- German security technocracy,
- Entente restorationism,
- anti-colonial nationalism,
- American armistice legitimacy,
- syndicalist underground,
- anarchist federation networks,
- totalist cadre infiltration.

## First Implementation Batch

The first playable batch should be:

- German Empire,
- Russia,
- French Republic,
- United Kingdom,
- Federal Republic,
- Combined Syndicates Remnant,
- American Union/National State,
- Pacific States,
- Japan,
- Ukraine.

These tags cover every central system: German hegemony, Russian revisionism, restored Entente politics, fragmented America, Pacific escalation, and the eastern frontier.

Each first-batch tag should receive an opening response path to the Postwar Reckoning:

- stabilize through liberal reconstruction,
- impose emergency controls,
- empower nationalist mobilization,
- bargain with labor,
- repress radicals,
- borrow from a foreign bloc,
- or export the crisis onto clients, colonies, or rivals.
