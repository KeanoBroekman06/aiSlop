Genereer een REST API in Python (Flask) voor een bibliotheek. 
- Entiteiten: Book, User, Loan
- CRUD-functionaliteit voor alle entiteiten
- Voeg validatie toe: een boek kan alleen worden geleend als het beschikbaar is
- Gebruik JSON responses

Leg uit wat deze code doet:
- Welke functies bestaan er?
- Welke input en output heeft elke functie?
- Waar kunnen fouten optreden?

Bekijk deze REST API-code en geef concrete verbeterpunten:
- Performance
- Veiligheid
- Code-structuur

Je bent een agent die een REST API specificeert voor een bibliotheek. 
- Beschrijf alle endpoints met method, parameters en responses
- Maak voorbeeld JSON responses
- Houd rekening met edge-cases, zoals niet-beschikbare boeken

Genereer unit tests en integration tests op basis van deze API-specificatie. 
- Test GET /books en POST /loans
- Controleer validatie en foutafhandeling
- Geef output in Python unittest of pytest

Gebruik mijn Mermaid-diagrammen van de bibliotheek-workflow en geef suggesties om de API te verbeteren of flows te vereenvoudigen.

Schrijf een bash-script dat automatisch:
- git add .
- git commit -m "Automated commit"
- git push origin main
- merge requests maakt als er nieuwe branches zijn

Leg in de CLI uit wat deze Python REST API doet. Geef een korte samenvatting van alle endpoints en functies.

Maak een technische README voor deze bibliotheek-API. 
- Beschrijf installatie, gebruik, en endpoints
- Voeg voorbeeldrequests en responses toe

Maak een ERD (Entity-Relationship Diagram) voor een bibliotheek. 
- Entiteiten: Book, User, Loan
- Relaties: 
    - Een Book kan in meerdere Loans voorkomen
    - Een User kan meerdere Loans hebben
- Genereer in Mermaid-code

Maak een sequence diagram in Mermaid voor een REST API van een bibliotheek. 
- Actor: User
- Endpoints: GET /books, POST /loans
- Laat zien hoe data van de database terugkomt naar de gebruiker

Maak een use-case diagram in Mermaid voor een bibliotheek-app. 
- Actors: User, Librarian
- Use-cases: Search Books, Borrow Book, Return Book, View Loan History, Add Book, Remove Book

Maak een flow-diagram in Mermaid voor het proces van een boek lenen:
- Start bij "Start"
- Beslis of boek beschikbaar is
- Ja: create loan record → update book status → notify user → End
- Nee: notify user → End

Maak een flowchart in Mermaid die de workflow van een AI-agent toont: 
- Agent ontvangt opdracht → analyseert specificatie → genereert API → schrijft tests → controleert resultaten → geeft feedback


DAG 3
"Maak een kort design document voor een casino webapp, inclusief tech stack, globale architectuur, belangrijke keuzes en risico’s."

"Visualiseer de architectuur van een mini-casino in Mermaid, inclusief Main Menu, games en shared components."

"Bedenk een overzicht voor client-side coin management in een webapp, inclusief mogelijke risico’s en oplossingen."

"Schrijf een logica-flow voor een Blackjack game in pseudo-code of een diagram."

"Bedenk een systeem voor achtergrond-rolls met zeldzaamheden en coin-verbruik."

"Bedenk extra features die de casino webapp leuker maken voor spelers, met UX in gedachten."

"Genereer een Mermaid diagram voor een casino webapp, met applicatie-overzicht van Main Menu, Blackjack, Roulette en Minefield."

"Maak een datastroomdiagram in Mermaid voor een casino game: van spelerinvoer tot coin-update."

"Maak een sequence diagram voor een Blackjack ronde met Hit/Stand en coin berekening."