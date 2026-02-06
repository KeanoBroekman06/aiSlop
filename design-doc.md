Frontend:

HTML5 / CSS3 / JavaScript (Vanilla JS)

Canvas API (voor roulette wheel animatie)

Assets & Libraries:

Afbeeldingen voor kaarten (via CDN)

CSS transitions & animations voor smooth UI

Browsers:

Chrome, Firefox, Edge (mobiel nog beperkt getest)

Optional future tools:

Frameworks zoals React of Vue voor schaalbaarheid

Node.js + Express voor server-side scoretracking

┌───────────────────┐
│   Main Menu Page  │
│ (Navigation:      │
│  Blackjack,       │
│  Roulette,        │
│  Minefield, etc.) │
└─────────┬─────────┘
          │
          ▼
┌─────────────────────┐
│  Game Pages         │
│ ┌───────────────┐   │
│ │ Blackjack     │   │
│ │ Logic + UI    │   │
│ └───────────────┘   │
│ ┌───────────────┐   │
│ │ Roulette      │   │
│ │ Logic + Canvas│   │
│ └───────────────┘   │
│ ┌───────────────┐   │
│ │ Background/    │  │
│ │ Reward system │   │
│ └───────────────┘   │
└─────────┬───────────┘
          │
          ▼
┌───────────────────┐
│ Coin Management   │
│ - Player coins    │
│ - Bets & payouts  │
└───────────────────┘

Vanilla JS en CSS: Simpel, snel te prototypen, geen extra dependencies.

Canvas voor Roulette: Geeft een animatie van draaiend wiel en laat future uitbreidingen toe (bijv. spin physics).

Deck & Cards via CDN: Vermijdt lokaal beheer van assets en houdt project lichtgewicht.

Rarity system voor backgrounds: Motiveert de speler om coins te gebruiken voor visuele beloningen.

Single-page UI per game: Minimaliseert page reloads en geeft directe feedback.

Performance issues: Lange background transitions of veel animaties kunnen mobiel vertragen.

State management: Alles gebeurt client-side; bij refresh gaat coinstand verloren.

Security: Geen server-side validatie → coins kunnen gemanipuleerd worden via console.

Scalability: Bij uitbreiding naar meer spellen of multiplayer kan vanilla JS beperkt zijn.

Randomness: Momenteel gebaseerd op Math.random(), wat niet cryptografisch veilig is voor echt gokgebruik.