# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game in Python to practice string handling, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Implement Hangman Game Logic

#### Description

Create the main game loop so the program picks a random word, accepts letter guesses, and updates game state until the player wins or loses.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Show current word progress as blanks and revealed letters (e.g., `_ a _ _ m a n`)
- Accept guesses one letter at a time
- Prevent repeated guess penalties for previously guessed letters
- Track and display remaining incorrect attempts
- Show a win message when the word is fully guessed
- Show a lose message and reveal the word when attempts run out

### 🛠️ Add User Feedback and Input Validation

#### Description

Improve UX by validating input, handling non-letter guesses, and giving clear game status updates.

#### Requirements
Completed program should:

- Reject empty input and non-alphabetic characters with a message
- Accept case-insensitive guesses (e.g., `A` and `a` are the same)
- Display the list of guessed letters so far
- Update the player after each guess (progress, remaining attempts, guessed letters)

