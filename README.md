# Hangman
Hangman is a classic game in which a player thinks of a word and the other player tries to guess that word within a certain amount of attempts.

This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it. 

## Milestone 2: Creating variables for the game

'milestone_2.py'

A simple code snippet in this file initializes the list of words to choose from. Then it uses the 'random' module to randomly select a word from the list. Finally, it asks for the user's input and checks if it is valid, printing the appropriate message.

## Milestone 3: Check if the guessed character is in the word

'milestone_3.py'

The code in this file is a modification of the previous one. There is a function 'ask_for_input()' that asks for the user's input in an infinite loop until the input is valid. There's also a 'check_guess()' function, which takes the user's guess as a parameter and checks if it is in the randomly chosen word.