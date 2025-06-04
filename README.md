# simpleRockPaperSecissorGame
A simple, client-side implementation of the classic Rock-Paper-Scissor game using only HTML and JavaScript.

## Description

This project contains a single HTML file (`index.html`) that displays three buttons—Rock, Paper, and Scissor. When clicked, each button:

1. Generates a random move for the computer.
2. Compares your selection against the computer’s move.
3. Displays the result (win, lose, or tie) in an alert popup.

## How to Play

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Click on one of the buttons: Rock, Paper, or Scissor.
4. A popup alert will show:
   - What you picked
   - What the computer picked
   - Whether you won, lost, or tied

## File Structure

rock-paper-scissor-game/
├── index.html
└── README.md

markdown
Copy
Edit

- `index.html`: Contains all the HTML and JavaScript code for the game.
- `README.md`: This file, providing project information and instructions.

## How It Works

- **Computer Move Generation**  
  Each time you click a button, the script generates a random number to determine the computer’s move.

- **Game Logic**  
  The player’s move is compared with the computer’s move using simple `if` statements. Based on the rules of the game:
  - Rock beats Scissor
  - Scissor beats Paper
  - Paper beats Rock
  - Same choices result in a tie

- **Result Display**  
  The outcome is shown using a JavaScript `alert()` with your choice, the computer's choice, and the result.

## Notes

- The code uses "Scissor" (singular). You may update it to "Scissors" (plural) for correctness if desired.
- Inline JavaScript is used. For cleaner code, it can be moved to an external JavaScript file in the future.
- The game is fully functional without any external libraries or frameworks.
