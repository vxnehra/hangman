
# Hangman Game in Python

 # Project Description

This is a simple text-based Hangman game in Python. In this game, the player is required to guess a hidden word by entering one letter at a time. The player has a limited number of attempts (6) before they lose the game and "hang the man". The game keeps track of the player's score by saving it to a file ('score.txt'), allowing the player to see their performance over time. The game will continue running until the player chooses not to play anymore.

# Features:
- Randomly selects words from a list to create a new game each time.
- Displays a "hangman" figure to visualize the number of incorrect guesses.
- Tracks the player's score, saving it in a file.
- user can only input valid guesses (one letter at a time) are accepted.

## How to Play
1. The game will display a random word with underscores to represent the hidden letters.
2. The user enters one letter at a time as a guess and replaces the unscore if correct
3. The game will tell the user whether the guessed letter is in the word or not.
4. If the user guesses the word before running out of attempts, they win and the score increases.
5. If the user uses up all 6 attempts without guessing the word correctly, they lose, and the score decreases. can go into negatives also
6. The score is saved to a file and will be displayed at the start of each new game.

# What I Learned:
Through this project, I improved my understanding of Python functions, loops, conditional statements, and file handling. This project also taught me how to work with user input to ensure that only valid guesses are allowed. file handling was a bit confusing for me and still is, but I think the more I keep practing usingfie handling the better I will get at it 

# Inputs Tried:
- I tested various word lengths (short and long words) to ensure the word selection works correctly(.random).
- Inputted both valid and invalid guesses to ensure that the game correctly handles these cases. For example, entering multiple characters, non-alphabetic characters, or repeating the same guess.
- Played multiple rounds to test score saving and loading.

# New Python Features
- I explored file handling in Python to load and save scores, using 'open()' with modes like 'r' and 'w' for reading and writing files.
- I also used basic error handling with 'try' and 'except' to prevent the program from crashing when the score file doesn't exist.
- I learned how to structure a game loop and handle user input within a while loop, allowing for continuous gameplay until the user chooses to stop.
# challenge
- I first made the game without the visual of the hangman but after I had finished the game seemed a bit boring so implementing the visual figure made the game come to life it was confusing making the figure but I had watched a youtube video of someone explaing how to get the spaces right etc.(making art almost)
- Another challenge I had was the saving game and loading game functions I had alot of help 
in the tutoring center trying to under stand these functions and how using try/except call would eliminate my errors when trying to load a game without it crashing 
