# Hangman Game - JavaScript

A simple Hangman game built using JavaScript, HTML, and CSS. This is a fun, interactive word-guessing game where players try to guess a hidden word by suggesting letters. Each incorrect guess results in a part of a stick figure being drawn, and the game ends when either the word is guessed or the figure is fully drawn.

## Features

- User-friendly interface with simple visuals
- Randomly selected words from a pre-defined list
- Tracks incorrect guesses and displays the hangman figure
- Displays remaining attempts and correctly guessed letters
- Allows multiple rounds of play

## How to Play

1. The game will display a series of underscores representing the letters of a hidden word.
2. You can guess a letter by clicking on a letter or typing it on the keyboard.
3. For each correct guess, the word will update, revealing the guessed letter(s).
4. For each incorrect guess, a part of the hangman figure will be drawn.
5. The game ends when you either guess the word or the figure is fully drawn (typically 6 wrong guesses).
6. A new word will be randomly selected, and the game starts again.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, etc.)
- No installation required, just open the `index.html` file in your browser.

### Running the Game

1. Clone or download the repository.
2. Open the `index.html` file in your preferred browser to start playing.

## Files

- `index.html`: The main HTML file containing the structure of the game.
- `style.css`: The styling file to add visual appeal to the game.
- `script.js`: The JavaScript file containing the game logic and functionality.

## Example Gameplay

1. The player sees a word represented as underscores (`_ _ _ _`).
2. The player guesses a letter, say "A."
   - If "A" is in the word, it replaces the corresponding underscores.
   - If "A" is incorrect, the hangman figure starts drawing.
3. The game continues until the word is guessed or the hangman figure is completed.

## Contributing

Feel free to fork this repository and contribute by improving the game! Pull requests are welcome.

## Acknowledgments

- Thanks to the open-source community for inspiration and resources!
