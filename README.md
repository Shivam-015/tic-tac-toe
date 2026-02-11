# Tic Tac Toe Web Application

## Overview

This project is a browser-based Tic Tac Toe game developed using HTML, CSS, and JavaScript.
It demonstrates core front-end development concepts including DOM manipulation, event handling, conditional logic, and responsive UI design.

The application allows two players to play alternately and automatically determines the winner or tie condition.


## Objective

The objective of this project is to implement game logic using JavaScript while maintaining a clean and responsive user interface using modern CSS techniques.


## Technology Stack

* HTML5 – Structure and layout
* CSS3 – Styling, Grid system, Flexbox, Glassmorphism effect
* JavaScript (ES6) – Game logic and state management


## Application Features

* Two-player gameplay (Player X and Player O)
* Automatic turn switching
* Winner detection logic
* Tie detection logic
* Winning combination highlighting
* Board reset functionality
* Responsive and centered layout


## System Architecture

The application follows a simple client-side architecture:

* `index.html` → UI structure
* `style.css` → Visual styling and layout
* `index.js` → Game logic and state handling

The game board state is maintained using a JavaScript array.
Winning conditions are predefined and evaluated after each move.


## Game Logic Flow

1. Initialize game state
2. Wait for player input (click event)
3. Update board and state array
4. Switch player turn
5. Check for winning combination
6. If winner found → highlight and disable board
7. If board filled without winner → declare tie
8. Allow reset using "New Game" button


## Installation & Usage

1. Clone or download the repository.
2. Open the project folder.
3. Run `index.html` in any modern web browser.
4. Start playing.

No external dependencies are required.


## Learning Outcomes

* DOM selection and manipulation
* Event-driven programming
* Conditional logic implementation
* Array-based state management
* CSS Grid layout implementation
* Basic game development principles


## Future Enhancements

* Single-player mode with AI
* Scoreboard implementation
* Sound effects and animations
* Improved UI transitions
* Mobile optimization enhancements


## Author

Developed as a front-end practice project to strengthen JavaScript logic-building and UI development skills.
