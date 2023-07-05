# NumberGuessing
# Number Guessing Game Project in Java

The Number Guessing Game project in Java is a simple game where the player attempts to guess a randomly generated number within a given range. The game provides feedback to the player after each guess, indicating whether the guess is too high or too low. The objective is to guess the correct number within the fewest number of attempts.

The project is implemented using Java programming language and provides a command-line interface for the game interaction. It demonstrates the use of random number generation, conditional statements, and user input handling.

## Features

The Number Guessing Game project includes the following features:

1. Random Number Generation: The game generates a random number within a specified range, which the player needs to guess.

2. User Input Handling: The project validates and handles user input to ensure that only valid guesses are accepted. It provides error messages for invalid inputs, such as non-numeric characters or guesses outside the specified range.

3. Guess Evaluation: After each guess, the game provides feedback to the player, indicating whether the guess is too high or too low compared to the target number.

4. Guess Count: The game keeps track of the number of guesses made by the player and displays it at the end of the game.

5. Play Again: After completing a game, the player has the option to play again. If chosen, a new random number is generated, and the game restarts.

## Project Structure

The project can be organized into the following components:

1. `Main`: The main class of the project that contains the entry point for the application. It handles the game flow, user input, and interacts with other classes.

2. `Game`: The `Game` class represents a single game instance. It generates a random number, keeps track of the number of guesses, and evaluates the player's guesses.

3. `InputHandler`: This class handles user input validation and parsing. It ensures that the user provides valid guesses within the specified range.

4. `Utils`: The `Utils` class contains utility methods used throughout the project, such as generating random numbers and displaying messages.

## Getting Started

To run the Number Guessing Game project, follow these steps:

1. Install Java Development Kit (JDK) on your system if not already installed.

2. Set up your preferred Java development environment (IDE) or use a text editor.

3. Create a new Java project and import the project files.

4. Build the project to ensure there are no compilation errors.

5. Run the `Main` class to start the game.

## Conclusion

The Number Guessing Game project in Java provides a simple yet entertaining game where players can test their guessing skills. It demonstrates the use of random number generation, user input handling, and conditional statements in Java. You can further enhance the project by adding features like difficulty levels, time limits, or graphical user interfaces to make the game more engaging.
