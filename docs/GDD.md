# Game Design Document: Escape to the Future

## 1. Project Concept
* **Speler:** Je bestuurt een Rocket.
* **Perspectief:** Top-down game.
* **Besturing:** Muis of toetsenbord. Muisklik of 'W' voegt thrust (stuwdruk) toe. Rechtermuisknop of spatiebalk wordt gebruikt om te schieten.
* **Doel:** Overleven en het eind-wormgat bereiken zonder vernietigd te worden, zonder dat de brandstof opraakt, en zonder opgeslokt te worden door het zwarte gat aan de onderkant van het scherm. De speler kan asteroïden vernietigen voor een kans op brandstof.

## 2. Basic Gameplay
* **Obstakels:** Asteroïden en kosmisch puin verschijnen vanaf de bovenkant en de zijkanten.
* **Interactie:** Spelers kunnen puin kapotschieten om brandstofkristallen te verzamelen.
* **Win/Verlies condities:**
  * **Winst:** Het bereiken van het wormgat (Wormhole).
  * **Verlies:** De speler sterft door schade, de brandstof raakt op (waardoor de raket stopt en in het zwarte gat valt), of de speler wordt opgezogen door het zwarte gat.

## 3. Sound & Effects
* **Geluidsieffecten:** Motorgebrom (engine hum), sci-fi achtergrondmuziek, schietgeluiden (pews), schade-geluiden en collectible sounds.
* **Visuele effecten:**
  * Kleine deeltjes (particles) bij de raketuitlaat.
  * Effecten bij het vernietigen van puin.
  * Visuele wervelingen bij het zwarte gat.
  * Screen-shake bij harde impacts.
* **Extra:** Het zwarte gat intensiveert gedurende de game met zwaardere particle-effecten.

## 4. Gameplay Mechanics
* **Moeilijkheidsgraad:** Naarmate het spel vordert verschijnen er meer asteroïden (met minder brandstofkristallen) en neemt de zwaartekracht van het zwarte gat toe. Dit maakt het moeilijker om voor de waarnemingshorizon (event-horizon) te blijven.
* **Power-ups:** Mogelijkheid tot tijdelijke onkwetsbaarheid of verschillende schietpatronen.
* **Restart:** Wanneer het spel eindigt, verschijnt er UI die de speler vraagt om opnieuw te proberen of de game af te sluiten.

## 5. User Interface (HUD)
* **Stats:** Een score bepaald door progressie en vernietigde asteroïden. De score neemt toe bij overleving en neemt af bij schade.
* **Health:** Levens worden weergegeven in een healthbar.
* **Fuel:** Een brandstofbalk (fuelbar). Als deze leeg is, stopt de beweging.
* **Progressie:** Een balk die aangeeft hoe dicht de speler bij het wormgat is.
* **Extra Velden:** Tijd- en scorevelden in de HUD.

## 6. Branding & Other Features (MoSCoW - Must)
* **Logo & Slogan:** Het splash-scherm toont het logo van Best Education B.V. en de slogan: *"Wij lanceren je de toekomst in!"*.
* **Rocket Design:** De raket lijkt op het logo van het bedrijf.
* **Educatie:** "Fun facts" over de opleiding worden getoond in de HUD.

## 7. Project Timeline & Milestones
| Milestone | Beschrijving | Deadline |
| :--- | :--- | :--- |
| #1 | Character motion & Test LVL (movement uitwerken) | 02-02 |
| #2 | Simpele 2D Graphics (speler, obstakels, back/foreground) | 04-02 |
| #3 | Scoring & UI (health-, progressie- en fuelbar) | 06-02 |
| #4 | Online Scores (statische scorepagina buiten het project) | 09-02 |
| #5 | Polish (bugfixes, definitieve graphics, SFX toevoegen) | 11-02 |

---
*Opmerking: Multiplayer is gemarkeerd als backlog-item en maakt geen deel uit van de Minimum Viable Product (MVP).*