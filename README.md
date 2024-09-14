# Guess the Number Game

## Overview
This project is a simple **Guess the Number** game implemented using HTML, CSS, and JavaScript. The game randomly selects a number within a specified range, and the player has to guess the correct number. The player receives hints after each guess, such as "too high" or "too low", and the game ends when the player guesses the correct number.

## Features
- Random number generation within a specified range.
- Player input for guessing numbers.
- Feedback provided on each guess (too high, too low, or correct).
- Option to reset the game and play again.
- Simple user interface with basic styling.

## How to Play
1. The game randomly selects a number within a specified range (e.g., 1 to 100).
2. Enter your guess in the input field and submit.
3. The game will provide feedback:
   - If the guess is too high, you'll see a message like "Your guess is too high."
   - If the guess is too low, you'll see a message like "Your guess is too low."
   - If the guess is correct, you'll see "Congratulations! You've guessed the right number."
4. Continue guessing until you find the correct number.
5. Click the "Play Again" button to restart the game with a new random number.

## Game Mechanics
- **Random Number Generation**: The game selects a random number at the start of each round.
- **Player Input**: Players input their guesses through an input field.
- **Feedback**: After each guess, the game provides feedback on whether the guess was too high, too low, or correct.
- **Game Reset**: A "Play Again" button allows the player to reset the game and generate a new random number.

## Installation
You can run this game locally by following the steps below:

### Steps:
1. Clone or download this repository.
2. Navigate to the project folder.
3. Open the `index.html` file in any modern browser to start playing.

## Files
- **index.html**: Contains the structure of the game interface.
- **style.css**: Styles the game and controls the appearance.
- **script.js**: Implements the game logic, including random number generation and player feedback.

## Technologies Used
- **HTML**: For creating the structure of the game interface.
- **CSS**: For adding basic styles to the game layout.
- **JavaScript**: For handling the game logic, including user input, feedback, and game resets.

## Future Enhancements
- Add a scoring system to track the number of attempts.
- Allow the user to set their own range for the random number.
- Implement difficulty levels (e.g., easy, medium, hard).
- Improve the user interface with more styling and animations.

```bash
git clone https://github.com/Joshb-hub/GuessNum.git
cd GuessNum
open index.html
