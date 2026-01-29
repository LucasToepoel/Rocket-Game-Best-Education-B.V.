# Game Design Document: Escape to the Future

## 1. Project Concept
* **Speler:** Je bestuurt een Rocket.
* **Perspectief:** Top-down game.
* **Besturing:** Muis of WASD-toetsen. Muisklik of 'W' voegt thrust (stuwdruk) toe om de raket te bewegen.
* **Doel:** Overleven en de eindbestemming bereiken zonder vernietigd te worden, zonder dat de brandstof opraakt, en zonder opgeslokt te worden door het zwarte gat aan de onderkant van het scherm.

## 2. Basic Gameplay
* **Obstakels:** Asteroïden en kosmisch puin verschijnen vanaf de bovenkant en zijkanten.
* **Interactie:** Spelers kunnen asteroïden vernietigen voor een kans om brandstofkristallen te verzamelen.
* **Win/Verlies condities:**
    * **Winst:** Het bereiken van het einddoel/platform.
    * **Verlies:** Speler sterft door schade, brandstof raakt op, of wordt opgezogen door het zwarte gat.

## 3. Sound & Effects
* **Geluidsieffecten:** Motorgebrom (engine hum), sci-fi achtergrondmuziek, 'pew-pew' geluiden, schade-geluiden en collectie-pings.
* **Visuele effecten:**
    * Kleine deeltjes (particles) bij de raketuitlaat.
    * Effecten bij het vernietigen van puin.
    * Visuele wervelingen bij het zwarte gat.
    * Screen-shake bij harde impacts.

## 4. Gameplay Mechanics
* **Moeilijkheidsgraad:** Naarmate het spel vordert verschijnen er meer asteroïden (met minder brandstofkristallen) en neemt de zwaartekracht van het zwarte gat toe.
* **Power-ups:** Mogelijkheid tot tijdelijke onkwetsbaarheid of verschillende schietpatronen.
* **Branding (MoSCoW - Must):** * De raket lijkt op het logo van Best Education B.V.
    * Splash screen toont het logo en de slogan: *"Wij lanceren je de toekomst in!"*.
    * "Fun facts" over de opleiding worden getoond in de HUD.

## 5. User Interface (HUD)
* **Stats:** Een score bepaald door progressie en vernietigde asteroïden.
* **Gezondheid:** Levens worden weergegeven in een healthbar.
* **Brandstof:** Fuel-bar die aangeeft hoeveel brandstof er nog over is.
* **Feedback:** Schade aan het schip verlaagt de score en gezondheid; lang overleven verhoogt de score.

## 6. Project Timeline & Milestones
| Milestone | Beschrijving | Deadline |
| :--- | :--- | :--- |
| #1 | Character motion en Test Level | 02-02 |
| #2 | Simpele 2D Graphics | 04-02 |
| #3 | Scoring en UI | 06-02 |
| #4 | Online Scores (Indien haalbaar) | 09-02 |
| #5 | Polish & Bugfixes | 11-02 |

---
*Opmerking: Multiplayer is gemarkeerd als backlog-item en maakt geen deel uit van de Minimum Viable Product (MVP).*
