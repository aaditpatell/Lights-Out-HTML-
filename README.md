# Lights-Out 

A classic 3x3 puzzle game built with vanilla JavaScript, HTML, and CSS. Click cells to toggle lights and their neighbors. Turn all lights off to win. The game features an intelligent hint system, move tracking, sound effects, and a responsive design that works on desktop and mobile.

How to Play

Click any cell on the 3x3 grid to toggle that cell and its four adjacent neighbors (up, down, left, right). The goal is simple: turn all lights off. Yellow cells are on, dark gray cells are off. Every move counts—track your progress with the move counter. Use the Hint button if you get stuck. It intelligently suggests the move that reduces the most lights, letting you solve puzzles by spamming hints or by playing strategically.

Features

- **3x3 Grid Puzzle**: Simple but satisfying puzzle mechanics
- **Intelligent Hint System**: Analyzes all possible moves and suggests the best one
- **Sound Effects**: Click sounds for interaction, celebratory chord progression when you win
- **Move Counter**: Track how many moves it took to solve
- **Solvable Puzzles**: All puzzles are generated from the solved state, guaranteeing a solution exists
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **No Dependencies**: Pure JavaScript—no libraries, no build steps, no backend

Play Online

The game is deployed and playable at: **link here**

Just open in your browser and start playing. No installation required.

Local Development

To run locally:
1. Download `index.html` and `package.json`
2. Open `index.html` in any modern web browser
3. Play immediately

That's it. No npm install, no build process, no server setup.

Technical Details

- **Frontend**: HTML5, CSS3, vanilla JavaScript
- **Audio**: Web Audio API for procedurally generated sounds (no audio files)
- **Deployment**: Vercel
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

Game Rules

- **Click a cell**: Toggles the cell and its 4 neighbors
- **Goal**: Turn all lights off
- **Win Condition**: All cells are dark gray
- **Hint**: Finds the move that makes the most progress toward solving

Sound Design

- **Click Sound**: 400Hz→200Hz sweep, 100ms duration (plays on every move)
- **Win Sound**: C5-E5-G5-C6 arpeggio, celebratory and satisfying
- **Volume**: 30% to avoid jarring the user


MIT License. Feel free to use, modify, and distribute.

