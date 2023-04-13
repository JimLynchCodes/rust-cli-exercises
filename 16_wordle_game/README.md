# Wordle Game
Create a cli tool that plays a letter guessing game like [Wordle](https://www.nytimes.com/games/wordle/index.html)!

___Disclaimer: We are not affiliated at all with Wordle or New York Times. This is simply just a toy project to practice building cli tools and coding in Rust.___

## Backstory
Imagine you want to build a fun word guessing game for your friends to play in the command line- like wordle, but _better!_

Well, for this challenge you'll do just that...

<br/>

## The Exercise
Write a cli tool that allows the user to play a wordle like game.

First, the game should think of a random word. It should be a valid engligh word!

Prompt the user to make a guess.

Only allow guesses that are the correct number of characters and are valid english words.

After a guess is made, it is "scored" and the letters are highlighted in a specific way:

- if the letter is in the correct position, it is highlighted GREEN.

- if the letter is in the word but incorrect position, it is highlighted YELLOW.

- if the letter is not in the word, it is highlighted YELLOW.

If the user guess all correct letters then they win! Display a nice winning messge here.

If the number of guesses reaches zero and correct word hasn't been guessed, the user loses! Display what the secret word was along with some kind of "better luck next time!" message. 

<br/>

## Tests
It's up to you to decide if / how you would unit test this. Definitely add unit tests for the pure logic functions!

Writing integration tests can be tricky for this one, but feel free to give it a go!
<br/>

## Skills Practiced

- Validating text input

- Generating random words

- Color highlighting text in the console 

- Validating if a given string is a word

- Recursive function calls

- Keeping track of an overall game state

<br/>

## Bonus

- Display a "keyboard" of already guessed and unguessed letters

- Allow the user to change the number of letters in the word and number of guesses in a game

- Allow the game to be played in languages other than english

- Write automated tests that play the game and assert there are no rendering mistakes
