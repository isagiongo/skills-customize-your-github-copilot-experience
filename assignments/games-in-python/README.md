
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman word-guessing game using Python strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Word Selection and Game Setup

#### Description
Create a Hangman game that chooses a random word from a predefined list and initializes the game state for the player.

#### Requirements
Completed program should:

- Randomly select a secret word from a predefined list.
- Initialize the hidden word display using underscores for unguessed letters.
- Track the number of remaining incorrect guesses.

### 🛠️ Guess Processing and Display

#### Description
Allow the player to enter letter guesses, update the displayed word progress, and track incorrect letters.

#### Requirements
Completed program should:

- Accept single-letter guesses from the player.
- Reveal correct letters in the hidden word display, e.g. `h _ n g m a n`.
- Keep a list of incorrect guesses and decrement remaining attempts for wrong letters.

### 🛠️ Game End and Feedback

#### Description
End the game when the player guesses the word or runs out of attempts, and display an appropriate win or lose message.

#### Requirements
Completed program should:

- Detect when the player has guessed all letters in the word.
- Detect when the player has used all allowed incorrect guesses.
- Print a win message if the word is solved, or a loss message and the correct word if attempts run out.

### 📝 Example

Example interaction:

```text
The word is: _ _ _ _ _ _
Guess a letter: a
Correct! The word is: _ a _ _ _ _
Guess a letter: e
Incorrect. You have 5 guesses left.
```
