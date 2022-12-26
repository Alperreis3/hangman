# Hangman

This code is a implementation of the classic word-guessing game, Hangman. When the code is run, a word is randomly chosen from a list of words and the user must guess the letters in the word one at a time. The user has a limited number of lives, and for each incorrect guess, a life is lost. If the user runs out of lives before guessing the word, they lose. If the user correctly guesses all the letters in the word, they win.

# Getting Started
To run this code, you will need a Python interpreter. The code also imports the word_list module from the hangman_words file and the stages list from the hangman_art file, which should be located in the same directory as the code.

# Usage
To play the game, run the code and follow the prompts. You will be asked to guess a letter, and the letter will be checked against the chosen word. If the letter is in the word, the blank spaces representing the word will be filled in with the correct letters. If the letter is not in the word, a life will be lost and a hangman drawing will be displayed showing the current state of the game. The game continues until either the word is correctly guessed or the user runs out of lives.

# Known Issues
The code does not currently handle input validation, so entering letters that are not part of the alphabet or multiple letters at a time may cause the code to crash.

# Future Development
* Implement input validation to handle invalid user input.
* Add the option for the user to choose the word to be guessed.
* Implement a scoring system to keep track of multiple rounds of the game.

# Contributors
This code was written by a single contributor.

# License
This code is provided as-is, with no warranties or guarantees. It may be used and modified for any purpose, commercial or otherwise.
