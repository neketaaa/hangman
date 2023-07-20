# Hangman
Hangman is a classic game in which a player thinks of a word and the other player tries to guess that word within a certain amount of attempts.

This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it. 

## Milestone 2: Creating variables for the game

'milestone_2.py'

A simple code snippet in this file initializes the list of words to choose from. Then it uses the 'random' module to randomly select a word from the list. Finally, it asks for the user's input and checks if it is valid, printing the appropriate message.

## Milestone 3: Check if the guessed character is in the word

'milestone_3.py'

The code in this file is a modification of the previous one. There is a function 'ask_for_input()' that asks for the user's input in an infinite loop until the input is valid. There's also a 'check_guess()' function, which takes the user's guess as a parameter and checks if it is in the randomly chosen word.

## Milestone 4: Create the Game class

'milestone_4.py'

The class Hangman uses modified functions created in previous milestone as self methods. It also has fields for all data required for this game. The check_guess() method checks if the input letter is in the word. If yes it updates the appropriate fields, othervise reduces num_lives by 1. The ask_for_input() method asks user to enter single letter in an infinite loop and checks if the input is valid.

## Milestone 5: Putting it all togather

'milestone_5.py'

The entire Hangman game logic is implemented in the 'milestone_5.py' file. It includes the class Hangman, which takes two parameters during initialization: a list of words to choose from and a number of lives. The class has methods ask_for_input() and check_guess() which ask for input in an infinite loop and check if the input is in the word, respectively. A separate function, play_game(), creates a Hangman object and calls its methods until either the win or loss conditions are met. To play the game in the console, the play_game() function can be called with list_of_words and num_lives passed to it as arguments.