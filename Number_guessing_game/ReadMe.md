# Number Guessing Game

This is a simple program written in C that allows users to play a number guessing game. The program generates a random number between 1 and 100, and the user has to guess it. The program provides hints after each guess, indicating whether the guess is too high or too low, until the user guesses the correct number.

## How to Play

1. Run the program.
2. The program will prompt you to guess a number between 1 and 100.
3. Enter your guess.
4. The program will provide feedback, telling you if your guess is too high or too low.
5. Keep guessing until you correctly guess the number.
6. Once you guess the correct number, the program will congratulate you and tell you how many attempts it took.

## Implementation Details

- The program utilizes the `rand()` function to generate a random number between 1 and 100.
- The random number generator is seeded using the current time to ensure a different sequence of random numbers each time the program is run.
- It employs a `do-while` loop to repeatedly prompt the user for guesses until the correct number is guessed.
- After each guess, the program provides hints to the user whether the guess is too high or too low.
- Once the correct number is guessed, the program displays a congratulatory message along with the number of attempts it took.

## Requirements

- C compiler (e.g., GCC) installed on your system.

## Usage

1. Compile the program using a C compiler.
2. Run the compiled executable.
3. Follow the on-screen instructions to play the game.

## Example

$ ./number_guessing_game
Welcome to the Number Guessing Game!
I have selected a number between 1 and 100.
Enter your guess: 50
Too high! Try again.
Enter your guess: 25
Too low! Try again.
Enter your guess: 37
Too high! Try again.
Enter your guess: 30
Too high! Try again.
Enter your guess: 28
Congratulations! You guessed the number 28 in 5 attempts!