# Hangman Game

![Hangman Game Demo](/public/hangman.gif) 

A classic Hangman game built using React. Try to guess the hidden word before you run out of incorrect guesses!

## Features

- Interactive gameplay with visual representation of the hangman.
- Choose letters to guess the hidden word.
- Tracks the number of wrong guesses.
- Option to restart the game and play again.

## How to Play

1. Clone this repository to your local machine.
2. Navigate to the project directory using the terminal.
3. Install the required dependencies by running `npm install`.
4. Start the development server with `npm start`.
5. Open your web browser and visit `http://localhost:3000` to play the Hangman game.
6. Click on the letters to make guesses. The game will show you the progress of your guessed word.
7. Keep guessing until you either guess the entire word or make too many wrong guesses.

## Customization

You can customize the game by adjusting the following options:

- Maximum allowed wrong guesses.
- Gallows images for different stages of the hangman.

These options are defined in the `Hangman` component's `defaultProps` at the beginning of the `Hangman.js` file.

## About

This project was created as a fun way to practice React development. It uses the concept of state management and component rendering in React to create an interactive game.

Feel free to explore the code and make any improvements or modifications you'd like. If you find any issues or have suggestions, please open an issue or submit a pull request.


## License

This project is licensed under the [MIT License](LICENSE).
