# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a command-line Hangman game in Python that uses string manipulation, loops, and user input. Students will practice control flow, input validation, and basic I/O.

## 📝 Tasks

### 🛠️ Implement Hangman Game

#### Description
Create a playable Hangman program that randomly selects a secret word from a predefined list, prompts the player to guess letters, displays the masked word state, and tracks remaining attempts. The program should handle repeated guesses and invalid input gracefully.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list (or file).
- Display the secret word as underscores for unguessed letters (e.g., `_ _ a _ _`).
- Accept single-letter guesses (case-insensitive) and update the display.
- Track and display letters already guessed (correct and incorrect).
- Limit the number of incorrect guesses (e.g., 6 attempts) and end the game when attempts are exhausted.
- End with a clear win or lose message and reveal the word on loss.
- Prevent counting the same incorrect guess multiple times.

#### Example interaction

```
Secret word: _ _ _ _ _
Guess a letter: a
Good guess! Current word: _ a _ _ _
Guess a letter: z
Incorrect. Attempts remaining: 5
Guessed letters: a, z
```


