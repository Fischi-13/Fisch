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
Aktiv: false
Klasse: null
Attack_damage: 4
Defence: 3
Block: 0
HP: 0/0
Gold: 0
Inventar: Leer
Status_Effekte: Keine
Aktueller_Raum_Index: -1
Besuchte_Raeume: []

---

## Run_Struktur
-- Die prozedural generierte Raumabfolge für den aktuellen oder nächsten Run. --
-- Format: Index: Raumtyp --
0: Start
1: Gegner
2: Fragezeichen
3: Event
4: Schmied
5: Gegner
6: Shop
7. Ruheort
8: Gegner
9: Gebiets_Boss_1
10: NPC
11: Fragezeichen
12: Gegner
13: Event
14: Raetsel
15: Ruheort
16: Shop
17: Gegner
18: Gegner
19: Gebiets_Boss_2
20: Schmied
21: Fragezeichen
22: Ruheort
23: Gegner
24: Event
25: Shop
26: Gegner
27: Raetsel
28: Ruheort
29: Final_Boss
