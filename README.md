# Pig – The Dice Game 🎲🐷

A clean, modern implementation of the classic **Pig** dice game for two players.

First player to reach **100 points** wins.

##  Gameplay Rules

- Two players take turns.
- In each turn, a player can roll the die as many times as they want:
  - Roll 2–6 → add the value to your **current turn score**
  - Roll **1** → lose all points from the current turn and your turn ends immediately
- Click **Hold** to safely add your current turn score to your total score and pass the turn.
- The first player to reach **≥ 100 points** wins the game.

**Core strategy**: balance greed (keep rolling for more points) vs safety (hold before you roll a 1).

## Features

- Two human players (Player 1 vs Player 2)
- Visual indication of the active player
- Real-time display of current turn score
- Animated dice (shows faces 1–6)
- Winner screen with background change & red name highlight
- One-click **New Game** reset
- Glassmorphism design with blur backdrop
- Fully responsive layout
- No external dependencies – pure HTML/CSS/JS

## Technologies

- HTML5
- CSS3 (Flexbox · CSS Grid · backdrop-filter · transitions · gradients)
- Vanilla JavaScript (ES6+)
  - DOM manipulation
  - Event delegation
  - Game state management
