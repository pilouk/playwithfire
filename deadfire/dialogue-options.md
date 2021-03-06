<!-- TITLE: Deadfire Dialogue Options Report-->
# Dialogue Options Report
Please note: These tables were created by hand, so they will not be updated for each patch unless I get around to automating table generation.

## Raw Data

Last update: December 2, 2018

- [Embedded Spreadsheet](/deadfire/dialogue-options/raw-data)
- [Google Sheet](https://docs.google.com/spreadsheets/d/1YtruDo0zpVQ3Z7fcdMH4JEo1R8aQSAH9G57BnQ-ekL0/).

## Attributes

### IsAttributeScoreValue

Count | Attribute | Score Min | Score Max | Character
--- | --- | --- | --- | ---
7 | Constitution | 11 | 18 | Watcher
7 | Dexterity | 11 | 16 | Watcher
36 | Intelligence | 5 | 20 | Watcher
44 | Might | 9 | 20 | Watcher
61 | Perception | 3 | 20 | Watcher
38 | Resolve | 0 | 18 | Watcher

#### Companion Options

Count | Attribute | Comparison | Score | Character
--- | --- | --- | --- | ---
1 | Might | GreaterThanOrEqualTo | 16 | Eder
1 | Intellect | GreaterThanOrEqualTo | 15 | Serafen

#### Low Score Options

Count | Attribute | Comparison | Score | Character
--- | --- | --- | --- | ---
2 | Intellect | LessThan | 8, 10 | Watcher
1 | Perception | LessThan | 8 | Watcher
1 | Resolve | LessThan | 8 | Watcher
2 | Might | LessThanOrEqualTo | 10 | Watcher

## Backgrounds

### IsBackground

Count | Background
--- | ---
21 | Aristocrat
20 | Scientist
19 | Mystic
18 | Scholar
17 | Mercenary
14 | Philosopher
12 | Merchant
12 | Raider
11 | Clergy
10 | Explorer
9 | Drifter
9 | Slave
8 | Dissident
8 | Laborer
7 | Hunter
5 | Artist
3 | Colonist
2 | Soldier
1 | Gentry

## Classes

### HasClass

Count | Class | Character
--- | --- | ---
25 | Cipher | Watcher
25 | Priest | Watcher
24 | Druid | Watcher
21 | Ranger | Watcher
13 | Wizard | Watcher
10 | Chanter | Watcher
9 | Monk | Watcher
7 | Paladin | Watcher
5 | Rogue | Watcher
3 | Barbarian | Watcher
1	| Monk | Xoti

### HasSubclass

Count | Subclass
--- | ---
25 | Priest_Magran
14 | Priest_Eothas
13 | Ranger_GhostHeart
12 | Priest_Berath
9 | Paladin_GoldpactKnights
7 | Priest_Wael
6 | Priest_Skaen
5 | Paladin_BleakWalkers
4 | Paladin_TheShieldBearersOfStElcga
4 | Rogue_Assassin
3 | Paladin_KindWayfarers
3 | Rogue_Trickster
2 | Barbarian_CorpseEater
1 | Chanter_Skald
1 | Druid_Fury
1 | Fighter_BlackJacket
1 | Monk_Nalpazca
1 | Paladin_TheSteelGarrote
1 | Ranger_Stalker
1 | Rogue_Streetfighter
1 | Wizard_Enchanter

## Companions

### CompanionAddRelationship

**Note:** There are ~100 more places where companions earn relationship points between each other, but only relationships with the Watcher are formatted here.

#### Aloth-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
11 | Aloth | Negative | Minor 
4 | Aloth | Negative | Average 
5 | Aloth | Negative | Major 
20 | Aloth | Positive | Minor
1 | Aloth | Positive | Average
1 | Aloth | Positive | Major

#### Eder-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
5 | Eder | Negative | Minor
6 | Eder | Negative | Average
4 | Eder | Negative | Major
3 | Eder | Positive | Minor
2 | Eder | Positive | Average
1 | Eder | Positive | Major

#### Maia-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
16 | Maia | Negative | Minor
4 | Maia | Negative | Average
9 | Maia | Negative | Major
22 | Maia | Positive | Minor
4 | Maia | Positive | Average
2 | Maia | Positive | Major

#### Pallegina-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
16 | Pallegina | Negative | Minor
5 | Pallegina | Negative | Average
24 | Pallegina | Negative | Major
15 | Pallegina | Positive | Minor
1 | Pallegina | Positive | Average
9 | Pallegina | Positive | Major

#### Serafen-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
27 | Serafen | Negative | Minor
24 | Serafen | Negative | Average
11 | Serafen | Negative | Major
56 | Serafen | Positive | Minor
22 | Serafen | Positive | Average
9 | Serafen | Positive | Major

#### Tekehu-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
20 | Tekehu | Negative | Minor
3 | Tekehu | Negative | Average
13 | Tekehu | Negative | Major
16 | Tekehu | Positive | Minor
2 | Tekehu | Positive | Average
3 | Tekehu | Positive | Major

#### Xoti-Watcher

Count | Companion | Axis | Strength
--- | --- | --- | ---
22 | Tekehu | Negative | Minor
12 | Tekehu | Negative | Average
11 | Tekehu | Negative | Major
38 | Tekehu | Positive | Minor
13 | Tekehu | Positive | Average
13 | Tekehu | Positive | Major


### IsCompanionActiveInParty

**Note:** The counts from `IsCompanionActiveInPartyOrPresent` were merged into the totals below.

Count | Companion
--- | ---
324 | Tekehu
289 | Xoti
273 | Eder
267 | Maia
266 | Pallegina
258 | Serafen
245 | Aloth
11 | Rekke
9 | Ydwin
6 | Konstanten
3 | Fessina

### IsCompanionRelationship

Count | Source | Target
--- | --- | ---
14 | Aloth | Eder
4 | Aloth | Tekehu
14 | Aloth | Watcher
8 | Eder | Aloth
15 | Eder | Watcher
11 | Maia | Watcher
1 | Pallegina | Tekehu
11 | Pallegina | Watcher
1 | Pallegina | Xoti
29 | Serafen | Watcher
12 | Tekehu | Watcher
9 | Xoti | Eder
5 | Xoti | Pallegina
34 | Xoti | Watcher
2 | Xoti | Xoti


#### Full Breakdown

Count | Source | Target | Relationship
--- | --- | --- | ---
2 | Aloth | Eder | VeryPositive
2 | Aloth | Eder | Positive
2 | Aloth | Eder | Neutral
4 | Aloth | Eder | Negative
4 | Aloth | Eder | VeryNegative
2 | Aloth | Tekehu | Negative
2 | Aloth | Tekehu | VeryNegative
3 | Aloth | Watcher | VeryPositive
2 | Aloth | Watcher | Positive
4 | Aloth | Watcher | Negative
5 | Aloth | Watcher | VeryNegative
4 | Eder | Aloth | Negative
4 | Eder | Aloth | VeryNegative
3 | Eder | Watcher | VeryPositive
3 | Eder | Watcher | Positive
1 | Eder | Watcher | Neutral
4 | Eder | Watcher | Negative
4 | Eder | Watcher | VeryNegative
4 | Maia | Watcher | VeryPositive
3 | Maia | Watcher | Positive
2 | Maia | Watcher | Negative
2 | Maia | Watcher | VeryNegative
1 | Pallegina | Tekehu | Negative
1 | Pallegina | Watcher | VeryPositive
2 | Pallegina | Watcher | Positive
1 | Pallegina | Watcher | Neutral
4 | Pallegina | Watcher | Negative
3 | Pallegina | Watcher | VeryNegative
1 | Pallegina | Xoti | Negative
7 | Serafen | Watcher | VeryPositive
5 | Serafen | Watcher | Positive
8 | Serafen | Watcher | Negative
9 | Serafen | Watcher | VeryNegative
4 | Tekehu | Watcher | VeryPositive
2 | Tekehu | Watcher | Positive
3 | Tekehu | Watcher | Negative
3 | Tekehu | Watcher | VeryNegative
7 | Xoti | Eder | VeryPositive
2 | Xoti | Eder | Positive
2 | Xoti | Pallegina | Negative
3 | Xoti | Pallegina | VeryNegative
12 | Xoti | Watcher | VeryPositive
11 | Xoti | Watcher | Positive
2 | Xoti | Watcher | Neutral
4 | Xoti | Watcher | Negative
5 | Xoti | Watcher | VeryNegative
1 | Xoti | Xoti | Negative
1 | Xoti | Xoti | VeryNegative


## Crew

### CrewMemberHasPersonality

Note: The `CrewMemberHasPersonality` function checks specific crew members for personalities, but crew member GUIDs are not exposed, so the totals below have been merged.

Count | Personality
--- | ---
6 | Ascetic
1 | Chatty
4 | Drunkard
8 | Enigmatic
3 | Fearless
5 | Greedy
8 | Impulsive
1 | Irreverent
3 | Malicious
8 | Religious
5 | Rowdy

### IsCrewCount

Count | Comparison | Crew Size
--- | --- | ---
2 | EqualTo | 0
5 | GreaterThan | 0
1 | GreaterThan | 1
6 | GreaterThan | 2
1 | GreaterThanOrEqualTo | 5

### IsCrewJobRanks

Count | Job | Comparison | Amount
--- | --- | --- | ---
2 | Cannoneer | GreaterThan | 1
2 | Cannoneer | GreaterThan | 3
1 | Cannoneer | GreaterThan | 4
2 | Cannoneer | GreaterThanOrEqualTo | 4
1 | Cannoneer | GreaterThanOrEqualTo | 5
1 | Cannoneer | GreaterThanOrEqualTo | 8
1 | Deckhand | GreaterThan | 4
3 | Deckhand | GreaterThanOrEqualTo | 3
2 | Deckhand | GreaterThanOrEqualTo | 10
2 | Deckhand | GreaterThanOrEqualTo | 8
1 | Deckhand | GreaterThanOrEqualTo | 12
1 | Deckhand | GreaterThanOrEqualTo | 2
1 | Deckhand | GreaterThanOrEqualTo | 4
1 | Deckhand | GreaterThanOrEqualTo | 5
1 | Deckhand | GreaterThanOrEqualTo | 6
1 | Deckhand | LessThan | 3
1 | Helmsman | GreaterThan | 1
3 | Helmsman | GreaterThanOrEqualTo | 3
2 | Helmsman | GreaterThanOrEqualTo | 2
1 | Helmsman | GreaterThanOrEqualTo | 1
1 | Helmsman | GreaterThanOrEqualTo | 4
1 | Navigator | GreaterThanOrEqualTo | 1
1 | Navigator | GreaterThanOrEqualTo | 2
1 | Navigator | GreaterThanOrEqualTo | 3


## Culture

### IsCulture

Count | Culture
--- | ---
157 | DeadfireArchipelago
62 | Rauatai
14 | OldVailia
13 | Aedyr
11 | TheLivingLands
7 | TheWhiteThatWends
6 | IxamitlPlains
3 | TheVailianRepublics
1 | Nassitaq
1 | PrincipiSenPatrena

## Deities

### IsDeity

Count | Deity
--- | ---
9 | Eothas
5 | Magran
4 | Skaen
3 | Berath
1 | Wael

## Disposition

### DispositionAddPoints

Count | Disposition | Change
--- | --- | ---
265 | Aggressive | Minor
48 | Aggressive | Average
13 | Aggressive | Major
222 | Benevolent | Minor
29 | Benevolent | Average
6 | Benevolent | Major
299 | Clever | Minor
10 | Clever | Average
2 | Clever | Major
125 | Cruel | Minor
32 | Cruel | Average
15 | Cruel | Major
142 | Diplomatic | Minor
6 | Diplomatic | Average
161 | Honest | Minor
19 | Honest | Average
3 | Honest | Major
168 | Passionate | Minor
18 | Passionate | Average
2 | Passionate | Major
246 | Rational | Minor
5 | Rational | Average
2 | Rational | Major
157 | Shady | Minor
44 | Shady | Average
3 | Shady | Major
280 | Stoic | Minor
11 | Stoic | Average
1 | Stoic | Major

### IsDisposition

Count | Disposition | Rank | Comparison
--- | --- | --- | ---
29 | Aggressive | Rank 2 | GreaterThanOrEqualTo
4 | Aggressive | Rank 3 | GreaterThanOrEqualTo
3 | Aggressive | Rank 1 | GreaterThanOrEqualTo
2 | Aggressive | Rank 2 | EqualTo
29 | Benevolent | Rank 2 | GreaterThanOrEqualTo
7 | Benevolent | Rank 1 | GreaterThanOrEqualTo
2 | Benevolent | None | EqualTo
2 | Benevolent | Rank 2 | EqualTo
2 | Benevolent | Rank 3 | GreaterThanOrEqualTo
1 | Benevolent | Rank 1 | EqualTo
10 | Clever | Rank 2 | GreaterThanOrEqualTo
3 | Clever | Rank 3 | GreaterThanOrEqualTo
2 | Clever | Rank 1 | GreaterThanOrEqualTo
1 | Clever | Rank 1 | EqualTo
1 | Clever | Rank 3 | EqualTo
40 | Cruel | Rank 2 | GreaterThanOrEqualTo
11 | Cruel | Rank 1 | GreaterThanOrEqualTo
7 | Cruel | Rank 3 | GreaterThanOrEqualTo
1 | Cruel | Rank 1 | EqualTo
1 | Cruel | Rank 2 | EqualTo
1 | Cruel | Rank 1 | GreaterThan
20 | Diplomatic | Rank 2 | GreaterThanOrEqualTo
6 | Diplomatic | Rank 1 | GreaterThanOrEqualTo
6 | Diplomatic | Rank 3 | GreaterThanOrEqualTo
1 | Diplomatic | Rank 1 | LessThanOrEqualTo
34 | Honest | Rank 2 | GreaterThanOrEqualTo
4 | Honest | Rank 1 | GreaterThanOrEqualTo
3 | Honest | Rank 3 | GreaterThanOrEqualTo
1 | Honest | Rank 1 | EqualTo
1 | Honest | Rank 2 | LessThan
18 | Passionate | Rank 2 | GreaterThanOrEqualTo
2 | Passionate | Rank 3 | GreaterThanOrEqualTo
1 | Passionate | None | GreaterThanOrEqualTo
1 | Passionate | Rank 1 | GreaterThanOrEqualTo
22 | Rational | Rank 2 | GreaterThanOrEqualTo
2 | Rational | Rank 3 | GreaterThanOrEqualTo
1 | Rational | Rank 1 | GreaterThanOrEqualTo
37 | Shady | Rank 2 | GreaterThanOrEqualTo
7 | Shady | Rank 1 | GreaterThanOrEqualTo
7 | Shady | Rank 3 | GreaterThanOrEqualTo
1 | Shady | Rank 2 | EqualTo
1 | Shady | Rank 1 | LessThan
13 | Stoic | Rank 2 | GreaterThanOrEqualTo
2 | Stoic | Rank 1 | GreaterThanOrEqualTo
2 | Stoic | Rank 3 | GreaterThanOrEqualTo
1 | Stoic | Rank 1 | EqualTo

## Gender

### IsGender

Count | Gender
--- | ---
8 | Female
4 | Male

## Paladin Orders

### IsPaladinOrder

**Note:** The counts from `HasSubclass` were merged into the totals below.

Count | Paladin Order
--- | ---
16 | GoldpactKnights
7 | BleakWalkers
4 | TheShieldBearersOfStElcga
3 | KindWayfarers
2 | TheSteelGarrote
1 | DarcozziPaladini

## Race

### IsRace

Count | Race
--- | ---
44 | Godlike
30 | Orlan
17 | Dwarf
10 | Aumaua
3 | Elf
2 | Human

### IsSubrace

Count | Subrace
--- | ---
102 | Island_Aumaua
31 | Fire_Godlike
25 | Coastal_Aumaua
25 | Death_Godlike
11 | Moon_Godlike
10 | Nature_Godlike
9 | Boreal_Dwarf
7 | Ocean_Human
5 | Mountain_Dwarf
5 | Snow_Elf
2 | Meadow_Human
1 | Wood_Elf

## Reputations

### IsReputation

**Note:** Specific comparisons were merged to produce totals for Bad/Good/Mixed rank types.

Count | Faction | Rank Type
--- | --- | ---
1 | FCT_00_Dawnstars | Bad
4 | FCT_00_Dawnstars | Good
1 | FCT_00_Dawnstars | Mixed
20 | FCT_00_Huana | Bad
40 | FCT_00_Huana | Good
2 | FCT_00_Huana | Mixed
4 | FCT_00_Neketaka | Bad
8 | FCT_00_Neketaka | Good
4 | FCT_00_Neketaka | Mixed
11 | FCT_00_Principi | Bad
46 | FCT_00_Principi | Good
3 | FCT_00_Principi | Mixed
14 | FCT_00_RDC | Bad
40 | FCT_00_RDC | Good
3 | FCT_00_RDC | Mixed
13 | FCT_00_VTC | Bad
35 | FCT_00_VTC | Good
2 | FCT_00_VTC | Mixed
0 | FCT_01_Tikawara_Huana | Bad
3 | FCT_01_Tikawara_Huana | Good
1 | FCT_01_Tikawara_Huana | Mixed
3 | FCT_06_Gullet_Roparu | Bad
31 | FCT_06_Gullet_Roparu | Good
2 | FCT_06_Gullet_Roparu | Mixed
15 | FCT_06_Slums_Criminals | Bad
35 | FCT_06_Slums_Criminals | Good
2 | FCT_06_Slums_Criminals | Mixed

### ReputationAddPoints

Count | Faction | Axis | Strength
--- | --- | --- | ---
15 | FCT_00_Dawnstars | Positive | Minor
4 | FCT_00_Dawnstars | Negative | Minor
3 | FCT_00_Dawnstars | Positive | Average
2 | FCT_00_Dawnstars | Positive | Major
1 | FCT_00_Dawnstars | Negative | Major
16 | FCT_00_Huana | Negative | Major
12 | FCT_00_Huana | Positive | Major
12 | FCT_00_Huana | Positive | Minor
9 | FCT_00_Huana | Positive | Average
8 | FCT_00_Huana | Negative | Average
7 | FCT_00_Huana | Negative | Minor
21 | FCT_00_Neketaka | Positive | Minor
9 | FCT_00_Neketaka | Positive | Average
3 | FCT_00_Neketaka | Negative | Average
2 | FCT_00_Neketaka | Negative | Minor
1 | FCT_00_Neketaka | Positive | Major
39 | FCT_00_Principi | Positive | Minor
17 | FCT_00_Principi | Positive | Major
11 | FCT_00_Principi | Positive | Average
4 | FCT_00_Principi | Negative | Major
3 | FCT_00_Principi | Negative | Minor
1 | FCT_00_Principi | Negative | Average
20 | FCT_00_RDC | Positive | Major
16 | FCT_00_RDC | Positive | Minor
10 | FCT_00_RDC | Negative | Major
9 | FCT_00_RDC | Positive | Average
5 | FCT_00_RDC | Negative | Average
5 | FCT_00_RDC | Negative | Minor
29 | FCT_00_VTC | Positive | Minor
19 | FCT_00_VTC | Negative | Minor
19 | FCT_00_VTC | Positive | Average
13 | FCT_00_VTC | Positive | Major
4 | FCT_00_VTC | Negative | Major
5 | FCT_01_Tikawara_Huana | Positive | Major
2 | FCT_01_Tikawara_Huana | Positive | Minor
1 | FCT_01_Tikawara_Huana | Negative | Average
1 | FCT_01_Tikawara_Huana | Negative | Major
1 | FCT_01_Tikawara_Huana | Positive | Average
8 | FCT_06_Gullet_Roparu | Positive | Minor
4 | FCT_06_Gullet_Roparu | Positive | Major
2 | FCT_06_Gullet_Roparu | Negative | Major
1 | FCT_06_Gullet_Roparu | Negative | Minor
14 | FCT_06_Slums_Criminals | Positive | Minor
6 | FCT_06_Slums_Criminals | Negative | Major
6 | FCT_06_Slums_Criminals | Negative | Minor
2 | FCT_06_Slums_Criminals | Positive | Average
4 | FCT_09_Port_Maje | Positive | Minor
1 | FCT_09_Port_Maje | Positive | Major

## Skills

### IsSkillValue

#### No Party Assist

Count | Type | Skill | Score Min | Score Max
--- | --- | --- | --- | ---
2 | Active | Arcana | 4 | 10
16 | Active | Athletics | 1 | 7
6 | Passive | Bluff | 3 | 12
2 | Passive | Diplomacy | 4 | 10
4 | Passive | History | 1 | 7
20 | Passive | Insight | 2 | 8
5 | Passive | Intimidate | 3 | 10
9 | Passive | Metaphysics | 3 | 6
9 | Passive | Religion | 2 | 12
9 | Active | Sleight of Hand | 3 | 10
1 | Active | Stealth | 4 | 4
7 | Passive | Streetwise | 2 | 12
8 | Passive | Survival | 1 | 6

#### Party Assist

Count | Type | Skill | Score Min | Score Max
--- | --- | --- | --- | ---
12 | Active | Alchemy | 2 | 15
23 | Active | Arcana | 1 | 18
25 | Active | Athletics | 2 | 11
120 | Passive | Bluff | 1 | 20
149 | Passive | Diplomacy | 1 | 17
3 | Active | Explosives | 4 | 9
62 | Passive | History | 1 | 17
137 | Passive | Insight | 1 | 17
126 | Passive | Intimidate | 1 | 18
7 | Active | Mechanics | 1 | 9
33 | Passive | Metaphysics | 2 | 15
28 | Passive | Religion | 1 | 12
26 | Active | Sleight of Hand | 2 | 15
7 | Active | Stealth | 2 | 10
83 | Passive | Streetwise | 1 | 20
28 | Passive | Survival | 2 | 14

#### Low Score Options

Count | Type | Skill | Comparison | Score | Party Assist
--- | --- | --- | --- | --- | ---
1 | Active | Athletics | LessThan | 5 | False
1 | Passive | Bluff | LessThan | 7 | True
1 | Passive | Bluff | LessThan | 13 | False
1 | Active | Stealth | LessThan | 2 | False