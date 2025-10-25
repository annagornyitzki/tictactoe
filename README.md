# tictactoe

A classic Tic Tac Toe game where you play as **X** against a basic AI (**O**). The game features a clean interface, restart functionality, and automatic board reset on win or tie.

## Features

- Play as X against a random-move AI (O)
- Stylish, responsive design
- "Restart" button to start a new game at any time
- Board automatically resets after a win or tie
- Visual highlight for the winning line

## How to Play

1. Open `tictactoe.html` in your web browser.
2. Click any empty tile to place your X.
3. The AI (O) will make its move automatically.
4. The game ends when someone wins or the board is full (tie).
5. Click the **Restart** button to start a new game at any time.

## Project Structure

```
tic-tac-toe/
├── tictactoe.html   # Main HTML file
├── tictactoe.js     # Game logic (JavaScript)
├── tictactoe.css    # Stylesheet
└── tictactoe-background.jpg (optional) # Background image
```

## Customization

- **AI Difficulty:** The AI currently picks random empty tiles. You can improve it by adding smarter logic in `aiMove()` in [`tictactoe.js`](tictactoe.js).
- **Styling:** Modify [`tictactoe.css`](tictactoe.css) to change colors, fonts, or layout.
- **Background:** Replace `tictactoe-background.jpg` with your own image for a custom background.

## Requirements

- Any modern web browser (Chrome, Firefox, Edge, Safari, etc.)

## Credits

Created by Anna Gornyitzki.  
Inspired by classic Tic Tac Toe.

---

Enjoy the game!
