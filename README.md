# Sudoku Game

A responsive browser-based Sudoku game built with a single HTML file containing inline CSS and JavaScript. The game generates new Sudoku puzzles, tracks time, and offers controls for hints, checking answers, solving the board, and clearing user input.

## Features

- 9x9 Sudoku board with interactive cells
- Difficulty levels: Easy, Medium, Hard
- Timer display for tracking playtime
- New game generation with randomized puzzles
- Check board for mistakes
- Hint system to fill one correct cell
- Solve board instantly
- Clear all user-entered values
- Keyboard support: arrow keys for navigation, `1-9` for entry, `Backspace` / `Delete` / `0` to erase

## Files

- `sudoku.html` — single-file implementation with styles, markup, and gameplay logic

## How to Run

1. Open `sudoku.html` in a web browser.
2. Select a difficulty level.
3. Use the board and number pad to fill in digits.
4. Use the control buttons to start a new game, check your board, get hints, solve, or clear entries.

## Controls

- `New Game` — generate a new puzzle
- `Check` — validate current entries against the solution
- `Hint` — fill one incorrect or empty cell with the correct number
- `Solve` — complete the board automatically
- `Clear` — remove all non-given user input

## Notes

- The puzzle is generated in-browser using a randomized backtracking algorithm.
- Pre-filled numbers are marked as given and cannot be changed.
- The timer resets when a new game starts.

## License

This project does not include an explicit license file. Feel free to use and modify it for personal or educational purposes.
