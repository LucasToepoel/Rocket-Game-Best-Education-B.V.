# Rocket-Game-Best-Education-B.V.
Examen Basis Programmeren van Games (K0788)
**Project:** Rocket Game – Best Education B.V.  
**Ontwikkelaar:** Lucas Toepoel

## 1. Documentatie Ontwikkelomgeving

### Hardware
* **Merk en Model:** ASUS Vivobook 16x
* **Processor:** 13th Gen Intel(R) Core(TM) i7-13700H
* **Werkgeheugen (RAM):** 40GB
* **Besturingssysteem:** Linux-Fedora

### Software & Tooling
* **Game Engine:** Godot Engine 4.6.
* **Code Editor:** Godot Built-in Editor / Rider (jetbrains).
* **Versiebeheer:** Git, GitHub.
* **Grafische software:** Aseprite.
* **Audio:** Audacity.

---

## 2. Logboek (Opdracht A)

| Datum | Tijd | Activiteit | Resultaat |
| :--- | :--- | :--- | :--- |
| 28-01-2026 | 1 uur | Overleg met docent over eisen en backlog. | scope en requirements bevestigd |
| 28-01-2026 | 1 uur | Analyse exameninstructies & engine keuze. | Startklaar voor Opdracht B. |
| 29-01-2026 | 0.5 uur | Inrichten Git repository en README. | Ontwikkelomgeving gedocumenteerd. |


---

## 3. Game Design Document (GDD)

### 1. Player Control
* **Speler:** Rocket
* **Perspectief:** Top-Down
* **Input:** [Muispositie / WASD]
* **Movement:** Momentum-based physics (thrust).

### 2. Basic Gameplay
* **Obstakels:** Asteroïden en kosmisch puin.
* **Spawn:** Vanaf de bovenkant en zijkanten van het scherm.
* **Doel:** Overleven en energie-kristallen verzamelen voor brandstof.
* **Win/Verlies:** Landen op platform (Win) of crashen/brandstof op (Verlies).

### 3. Sound & Effects
* **Audio:** Engine hum, impact sounds, crystal pings.
* **Particles:** Ion-trails achter de rocket, stofwolken bij botsingen.
* **Extra:** Screen-shake bij harde impacts.

### 4. Gameplay Mechanics (MoSCoW)
* **Must:** Startmenu, besturing, win/verlies condities, Best Education B.V. branding.
* **Should:** Score bijhouden en toenemende moeilijkheidsgraad (zwaartekracht zwarte gat).
* **Branding:** Logo op de rocket, slogan "Wij lanceren je de toekomst in!" in het win-scherm.


## 4. Versiebeheer Strategie
Ik maak gebruik van een online Git repository. Wijzigingen worden dagelijks gepusht met duidelijke commit-messages die beschrijven wat er is toegevoegd, verwijderd of aangepast.
