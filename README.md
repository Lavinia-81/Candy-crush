# Candy Crush
Classic Match‑Three Puzzle Game — HTML • CSS • JavaScript  
Live Demo: https://lavinia-81.github.io/Candy-crush/

A simple, interactive Candy Crush–style game built using vanilla HTML, CSS, and JavaScript.
This project was created early in my learning journey to explore DOM manipulation, event handling, game loops, and dynamic UI updates.

---

## Overview
Candy Crush is a match‑three puzzle game where players drag and swap candies to form horizontal or vertical matches.
Matched candies disappear, new candies fall into place, and the score increases dynamically.

This project demonstrates:
- grid‑based game logic
- drag‑and‑drop events
- DOM updates in real time
- scoring mechanics
- responsive layout
- clean separation between structure, style, and logic

---

## Features
### Core Gameplay
- Drag and drop candies
- Match three or more identical candies
- Clear matched candies automatically
- Cascading effect: new candies fall into place
- Score increases based on match size

---

### UI & Design
- Responsive grid layout
- CSS‑based styling
- Smooth transitions and visual feedback

### JavaScript Logic
- Board initialization
- Candy swapping
- Match detection
- Candy clearing
- Gravity effect (candies falling)
- Score tracking
- Game loop updates

---

## Project Structure
```
Candy-crush/
│
├── index.html        # Game board structure
├── style.css         # Visual design and layout
├── app.js            # Game logic and interactivity
│
└── README.md         # Documentation
```
A clean, minimal structure focused on clarity and learning.

---

## How to Play
- Open index.html in your browser.
- The candy grid will appear.
- Drag one candy onto another to swap them.
- If the swap creates a match of 3+ candies:
- - They disappear
  - New candies fall into place
  - Your score increases
- Continue matching candies to increase your score.
- The game ends when no more valid moves remain.

---

## Key Concepts Demonstrated
- DOM Manipulation: Creating and updating the game board dynamically
- Event Handling: Drag‑and‑drop interactions
- Game Loop: Continuous checking for matches
- Responsive Design: Works on desktop and mobile
- Algorithmic Thinking: Match detection and cascading logic

---

## Getting Started
Clone the repository:
```
git clone https://github.com/Lavinia-81/Candy-crush.git
cd Candy-crush
Open the game:

open index.html
Or simply double‑click the file in your file explorer.
```

---

## Future Enhancements
- Add animations for candy clearing
- Add sound effects
- Add levels and difficulty progression
- Add a timer or move counter
- Add a leaderboard
- Add special candies (bombs, striped candies, etc.)

---

## Purpose of This Project
This mini‑game represents one of my earliest JavaScript projects.
It helped me understand:
- how game logic works
- how to manipulate the DOM
- how to build interactive UI components
- how to structure small front‑end projects

It remains in my portfolio as a milestone in my progression from beginner to advanced front‑end and full‑stack development.

---

## Contributions
Contributions are welcome.
Feel free to fork the repository and submit a pull request.
