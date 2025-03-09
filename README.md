*****
# Tic-Tac-Toe Game

## Overview
This project is a simple **Tic-Tac-Toe** game built using **HTML, CSS, and JavaScript**. The game is played between two players who take turns marking spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features
- Interactive 3×3 grid.
- Two-player mode.
- Displays winner or draw message.
- Reset button to restart the game.

## Requirements
- A web browser (Chrome, Firefox, Edge, etc.)
- A text editor (VS Code, Sublime Text, Notepad++, etc.)

## Project Structure
```
/tic-tac-toe/
│── index.html     # HTML structure
│── style.css      # Styling of the game
│── script.js      # Game logic
```

## Instructions to Set Up and Run
1. **Download or Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe.git
   ```
2. **Navigate to the Project Folder**
   ```bash
   cd tic-tac-toe
   ```
3. **Open the `index.html` File in a Browser**
   - You can simply double-click `index.html` or open it using Live Server in VS Code.

## How to Play
1. Player 1 starts as **'X'**, and Player 2 is **'O'**.
2. Click on an empty cell to make a move.
3. The game automatically checks for a winner or a draw.
4. If a player wins, a message will be displayed.
5. Click the "Reset" button to play again.

## Technologies Used
- **HTML**: Structure of the game board.
- **CSS**: Styling the game (grid, buttons, animations).
- **JavaScript**: Game logic, turn-based actions, win conditions.

## Example Code Snippet
```html
<div class="board">
  <div class="cell" data-index="0"></div>
  <div class="cell" data-index="1"></div>
  <div class="cell" data-index="2"></div>
  <div class="cell" data-index="3"></div>
  <div class="cell" data-index="4"></div>
  <div class="cell" data-index="5"></div>
  <div class="cell" data-index="6"></div>
  <div class="cell" data-index="7"></div>
  <div class="cell" data-index="8"></div>
</div>
```

## Future Improvements
- Add a **single-player mode** with AI.
- Improve UI with **animations** and sound effects.
- Keep track of **player scores**.

## License
This project is open-source and available under the **MIT License**.

---
Happy Coding! 🎮

