# Tic Tac Toe

A classic Tic Tac Toe game built with HTML, CSS, and JavaScript.

<div align="center">
  <img src="https://github.com/annagornyitzki/tictactoe/blob/main/tictactoe-gameplay.png?raw=true" width="550"/>
</div>

**Controls**
- Click any empty tile to place your **X**
- Press **Restart** to start a new game

Play it here [Live Game](https://annagornyitzki.github.io/tictactoe/)

## Overview
This project is a simple implementation of the traditional Tic Tac Toe game. You play as **X** against a basic AI (**O**) that randomly selects available tiles. The objective is to align three of your marks horizontally, vertically, or diagonally before the AI does.

## Project Structure
- `index.html`: The main HTML file that serves as the entry point for the game.
- `tictactoe.css`: Contains the styles for the game board and UI elements.
- `tictactoe.js`: The main JavaScript file that handles game logic and AI behavior.

## Game Logic
The game logic is implemented in `tictactoe.js`, which includes:
- **Player and AI Moves**: Handles tile selection and random move generation for the AI.
- **Win and Tie Detection**: Checks for all winning combinations or a full board to determine the result.
- **Board Reset**: Automatically resets the game state after a win or tie.

## UI/UX Design
The user interface and experience focus on clarity and playability. Key elements include:
- **Responsive Layout**: Ensures a clean display across devices.
- **Winning Highlight**: The winning combination is visually emphasized.
- **Restart Button**: Immediate access to start a new round of play.

## Customization

- **AI Difficulty:** The AI currently picks random empty tiles. You can improve it by adding smarter logic in `aiMove()` in [`tictactoe.js`](tictactoe.js).
- **Styling:** Modify [`tictactoe.css`](tictactoe.css) to change colors, fonts, or layout.
- **Background:** Replace `tictactoe-background.jpg` with your own image for a custom background.
  
## How to Run

1. Play it here [Live Game](https://annagornyitzki.github.io/tictactoe/)
2. Open `index.html` in a web browser to start the game.
   


