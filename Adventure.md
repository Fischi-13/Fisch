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
Defence: 3
Block: 0
HP: 50/50
Gold: 0
 
Kartenstapel: [Angriff1xA (1 AP), Angriff2xA (1 AP), Angriff3xA (2 AP), Block1xB (1 AP)]
Hand: []
Ablagestapel: []
AP: 3

Inventar: []
Status_Effekte: Keine
Stacks: {Gift: 0, Lust: 0, Schwäche: 0}
Aktueller_Raum_Index: 0
Besuchte_Raeume: []

---

## Run_Struktur
-- Die prozedural generierte Raumabfolge für den aktuellen oder nächsten Run. --
-- Format: Index: Raumtyp --
0: Start
1: Gegner
2: Fragezeichen
3: Gegner
4: Event
5: Schmied
6: Gegner
7: Ruheort
8: Shop
9: Gebiets_Boss_1
10: Gegner
11: NPC
12: Fragezeichen
13: Gegner
14: Raetsel
15: Schmied
16: Gegner
17: Shop
18: Ruheort
19: Gebiets_Boss_2
20: Gegner
21: Event
22: Fragezeichen
23: Gegner
24: Shop
25: Gebiets_Boss_3
26: Ruheort
27: Gegner
28: Final_Boss
