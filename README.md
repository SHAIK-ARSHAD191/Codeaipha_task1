# Hangman Game

A simple command-line implementation of the classic Hangman word-guessing game in Python.

## About

This is a fun interactive game where you try to guess a hidden word by suggesting letters. You have 6 incorrect guesses before the game is over. The game randomly selects a word from a predefined list and reveals your correct guesses while tracking your wrong attempts.

## How to Play

1. Run the game with Python
2. The game will display blank underscores for each letter in the hidden word
3. Guess one letter at a time
4. If your letter is correct, it appears in the word
5. If your letter is wrong, your incorrect guess counter decreases
6. Win by guessing all letters before running out of guesses!

## Requirements

- Python 3.x

## Running the Game

```bash
python hangman_game.py
```

## Game Rules

- You have **6 incorrect guesses** allowed
- Enter one letter at a time
- Letters must be alphabetic characters
- Duplicate guesses are not allowed
- The game ends when you either:
  - **Win**: Correctly guess all letters in the word
  - **Lose**: Run out of incorrect guesses

## Word List

The game uses a predefined list of words:
- python
- hangman
- coding
- random
- loops

## Example Gameplay

```
Welcome! guess the word
you have 6 incorrect guesses allowed.

Word: _ _ _ _ _ _
Guess a letter: e
Correct!

Word: _ e _ _ _ _
Guess a letter: a
Wrong! Incorrect guesses left: 5
```

## Features

- Input validation (only accepts single alphabetic letters)
- Prevents duplicate guesses
- Real-time feedback on correct/incorrect guesses
- Displays remaining incorrect guesses
- Shows the final word upon game completion
