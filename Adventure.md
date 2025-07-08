<!-- Adventure.md - Single Source of Truth für den Spielzustand -->
<!-- Dieses Dokument wird von einem externen Skript gelesen und aktualisiert. -->

## Player_Profile
-- Globale Daten, die zwischen den Runs bestehen bleiben. --
Name: Lukas
Freigeschaltete_Klassen: Krieger
Meta_Waehrung: 0
Schwierigkeitsgrad: Normal

---

## Aktueller_Run
-- Daten, die nur für den aktuellen Durchlauf gelten. Werden bei Run-Start zurückgesetzt. --
Aktiv: true
Klasse: Krieger
Standarddeck für Klasse: Angriff1xA (1 AP), Angriff2xA (1 AP), Angriff3xA (2 AP), Block1xB (1 AP)
Attack_damage: 2
Block: 0
HP: 25/25
Gold: 0
Spitzname: Cumdump
 
Kartenstapel: []
Hand: Angriff1xA (1 AP), Angriff2xA (1 AP), Angriff3xA (2 AP), Block1xB (1 AP)
Ablagestapel: []
AP: 5

Inventar: []
Status_Effekte: Keine
Stacks: {Gift: 0, Lust: 0, Schwäche: 0}
Aktueller_Raum_Index: 35
Besuchte_Raeume: 34,35

---

## Run_Struktur
-- Die prozedural generierte Raumabfolge für den aktuellen oder nächsten Run. --
-- Format: Index: Raumtyp --
Räume: [
0: Start
1: Fragezeichen
2: Gegner
3: Gegner
4: NPC
5: Shop
6: Event
7: Gegner
8: Schmied
9: Ruheort
10: Fragezeichen
11: Gegner
12: NPC
13: Shop
14: Gegner
15: Event
16: Ruheort
17: Gegner
18: Schmied
19: Gebiets_Boss_1
20: NPC
21: Gegner
22: Fragezeichen
23: Ruheort
24: Gegner
25: Shop
26: Event
27: Gegner
28: NPC
29: Schmied
30: Gegner
31: Gegner
32: Ruheort
33: Shop
34: Fragezeichen
35: Gegner
36: Raetsel
37: Event
38: Gegner
39: Gebiets_Boss_2
40: NPC
41: Ruheort
42: Schmied
43: Gegner
44: Shop
45: Event
46: Gegner
47: Fragezeichen
48: NPC
49: Gegner
50: Gegner
51: Ruheort
52: Gebiets_Boss_3
53: Schmied
54: Gegner
55: Event
56: NPC
57: Fragezeichen
58: Gegner
59: Shop
60: Final_Boss
]
