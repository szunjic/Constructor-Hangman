# Constructor-Hangman — Advanced JavaScript

#### HW #9 for The Coding Bootcamp at UT Austin

For this assignment, I created a Hangman command-line game using constructor functions.

My game receives user input using the ‘Inquirer’ npm package. 

I created the following constructor functions:

	* Word: Contains word specific logic and data; Used to create an object representing the current word the user is attempting to guess.  

	* Letter: Contains letter specific logic and data; Used for each letter in the current word. Each letter object either displays an underlying character, or a blank placeholder (an underscore), depending on whether or not the user has guessed the letter.

Each constructer function is contained within its own file and is exported and required wherever needed. 

The game keeps track of the user’s remaining guesses and prompts the user if they would like to end the game if none remain.