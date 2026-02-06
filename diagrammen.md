Maak een ERD (Entity-Relationship Diagram) voor een bibliotheek. 
- Entiteiten: Book, User, Loan
- Attributen per entiteit:
    - Book: id, title, author, isbn, available
    - User: id, name, email, membership_date
    - Loan: id, book_id, user_id, loan_date, return_date
- Relaties: 
    - Een Book kan in meerdere Loans voorkomen
    - Een User kan meerdere Loans hebben
Genereer dit in Mermaid ERD-syntaxis.

Maak een sequence diagram in Mermaid voor een REST API van een bibliotheek. 
- Actor: User
- API end-points: GET /books, POST /loans
- Interacties:
    1. User vraagt lijst van beschikbare boeken op
    2. API haalt boeken op uit database en geeft JSON terug
    3. User leent een boek via POST /loans
    4. API maakt loan record aan en geeft bevestiging terug

Maak een use-case diagram in Mermaid voor een bibliotheek-app. 
- Actors: User, Librarian
- Use-cases voor User: Search Books, Borrow Book, Return Book, View Loan History
- Use-cases voor Librarian: Add Book, Remove Book, Update Book Info, View All Loans

Maak een flow-diagram in Mermaid voor het proces van een boek lenen in een bibliotheek. 
- Start bij 'Start'
- Beslis of boek beschikbaar is
    - Ja: create loan record, update book status, notify user, einde
    - Nee: notify user dat boek niet beschikbaar is, einde


DAG 3
# AI Slop Casino Diagrammen

## 1. Applicatie-overzicht
```mermaid
graph TD
    A[Main Menu] --> B[Blackjack Page]
    A --> C[Roulette Page]
    A --> D[Minefield Page]
    B --> E[Deck & Card Logic]
    B --> F[Player Actions: Hit/Stand]
    C --> G[Roulette Wheel Logic]
    C --> H[Bet & Result Calculation]
    E --> I[Card Images via CDN]
    F --> J[Coin Management]
    H --> J
    D --> K[Minefield Logic]
    J --> L[Coins Display]
    L --> A

sequenceDiagram
    participant User as Player
    participant UI as Game UI
    participant Logic as Game Logic
    participant Assets as Assets/CDN

    User->>UI: Start game / place bet
    UI->>Logic: Validate bet & start round
    Logic->>Assets: Load card or wheel images
    Assets-->>Logic: Return images
    Logic-->>UI: Update game state (cards/wheel result)
    UI-->>User: Display updated hand / spin result
    Logic->>Logic: Calculate win/loss
    Logic-->>UI: Update coins
    UI-->>User: Display coins and messages


---

# **`prompts.md`**

```markdown
# Gebruikte Prompts

1. Voor het genereren van user stories:

2. Voor het maken van een design document:

