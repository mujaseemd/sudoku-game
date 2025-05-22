# Sudoku App

This is a fully functional, visually appealing, responsive Sudoku web application implemented as a single HTML file with inline CSS and JavaScript.

## Features

- **Responsive Design**: Works well on both desktop and mobile devices.
- **Three Difficulty Levels**: Easy, Medium, and Hard with varying number of pre-filled cells.
- **Real-time Mistake Tracking**: Counts mistakes as you input numbers and disables the board after 3 mistakes.
- **Instant Validation on Input**: Each entered number is validated immediately against the solution.
- **Manual Check Button**: Allows full board validation to confirm your solution.
- **Reset Button**: Clears your inputs and resets the current puzzle.
- **New Game Button**: Generates a new random puzzle based on the selected difficulty.
- **Clear Visual Feedback**: Highlights invalid inputs and shows messages for mistakes, completion, or failure.
- **Accessible**: Uses ARIA roles and labels for better accessibility.

## How to Use

1. Open the `sudoku.html` file in any modern web browser.
2. Select a difficulty level from Easy, Medium, or Hard.
3. Click "New Game" to generate a new Sudoku puzzle.
4. Fill in the empty cells by typing numbers 1-9.
5. Errors are highlighted in real-time, and if you make 3 mistakes, the game will automatically end with a failure message.
6. You can click "Check" anytime to validate your solution.
7. Use the "Reset" button to clear any inputs and retry the current puzzle.
8. When you've completed the puzzle correctly, you'll see a congratulatory message.

## Technical Details

- The Sudoku board is generated using a backtracking algorithm that creates a valid solution.
- The puzzle is then created by removing cells according to the chosen difficulty.
- Input validation is handled on each cell dynamically.

## Dependencies

- This app has no external dependencies and runs fully client-side in a web browser.
