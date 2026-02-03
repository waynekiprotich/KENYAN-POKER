# KENYAN-POKER

react based web game implementation of the popular Kenyan card game,Kadi players compete against a computer AI to be the first to empty their hand while navigating strategic " power cards" and penalty stacks

# Gameplay Features

Classic Kadi Rules: Match cards by Suit or Rank to discard.

Special Power Cards:

Question (Q or 8): Forces the next player to provide a matching Answer card.

Penalty (2, 3, or Joker): Forces the opponent to draw cards (2, 3, or 5 respectively).

Jump (J) & Kickback (K): Skips the opponent's turn.

Penalty Stacking: Defend against draw penalties by playing a matching penalty card or an Ace.

Niko Kadi: You must declare "Niko Kadi" when you have only one card left to win legally.

Winning Condition: You must end the game on a valid "Answer" card or a "Question + Answer" combo.

 # Tech Stack
Framework: React 19.

Build Tool: Vite.

Routing: React Router DOM.

API: Deck of Cards API for dynamic card assets.

State Management: Custom React hooks (useKadiDeck) for deck synchronization and reshuffling logic.

🛠️ Project Structure
src/components/: Reusable UI components for hands, buttons, and the play area.

src/pages/: Main application views (Home, GameBoard, Rules).

src/utils/gameLogic.js: The core engine handling move validation, AI decision-making, and penalty calculations.

src/hooks/: Custom hooks for managing game state and deck operations.

