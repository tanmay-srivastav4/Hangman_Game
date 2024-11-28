# Hangman Game
A simple implementation of the classic Hangman game in Python where players attempt to guess the letters of a randomly chosen word within a limited number of attempts.


## Features
- Randomly selects a word from a predefined list.
- Displays the progress of the guessed word with underscores and revealed letters.
- Keeps track of the number of remaining attempts.
- Provides feedback on correct and incorrect guesses.
- Ends the game with a win or loss message.


## How to Play
1. Run the Python script in the terminal or preferred IDE.
2. A random word is chosen from a predefined list of words, and the game starts.
3. User will have 10 attempts to guess the word.
4. Guess one letter at a time by typing it in the terminal.
5. Correct guesses reveal the letter(s) in their respective positions. Incorrect guesses reduce user's remaining attempts.
6. Win the game by guessing the word before the attempts run out.


## Game Rules
- Only one letter can be guessed at a time.
- Repeated guesses of the same letter are allowed but won't penalize the user further.
- The game ends either when:
  - All the letters of the word are guessed correctly (win).
  - User run out of attempts (loss).


## Prerequisites
- Python 3.x installed on your system.


## How to Run
1. Clone or download the repository containing this script.
   ```
   git clone https://github.com/tanmay-srivastav4/Hangman_Game
   ```
2. Open a terminal and navigate to the folder where the script is saved.
   ```
   cd Hagman_Game
   ```
3. Run the script using the following command:
   ```
   python hangman.py
   ```

## Example Gameplay
  ```
  Welcome to Hangman!
  _ _ _ _ _ _
  Guess a letter: p
  _ p _ _ _ _
  Guess a letter: x
  That letter doesn't appear in the word.
  Attempts remaining: 9

  ```
