# Higher Or Lower Game
Create a cli tool that plays the higher or lower game!

<br/>

## Backstory
Imagine you want to build a fun number guessing game for your friends to play in the command line.

Well, for this challenge you'll do just that...

<br/>

## The Exercise
Write a cli tool that allows the user to play a number guessing game.

First, the game should think of a random integer between 0 and 100.

Prompt the user to make a guess.

Only allow guesses that are valid integers with the possible range.

After a guess is made, it is "scored" and response is given:

- If the number is equal to the secret number, the user wins! Print the number of guesses it took.

- If the secret number is higher than the guessed number, respond something like, "your guess was too low".

- If the secret number is lower than the guessed number, respond something like, "your guess was too high".

You can optionally add a maximum number of guesses. If the remaining guesses reaches zero and correct number hasn't been guessed, the user loses! Display what the secret number was along with some kind of "better luck next time!" message. 

<br/>

## Tests
Add unit tests for the pure logic functions here.

Writing integration tests can be tricky for this one, but feel free to give it a go!

<br/>

## Skills Practiced

- Validating integer input

- Generating a random uint

- Recursive function calls

- Validating if a given string is a word

- Keeping track of an overall game state

<br/>

## Bonus

- Add in a maximum number of guess or the user loses.

- Accept arguments or flags for changing the maximum secret number and number of guesses the user is allowed. 

