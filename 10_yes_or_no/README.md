# Yes or No
Create a cli tool that asks the user a yes or no question!

<br/>

## Backstory
Imagine you want to make a cli tool that can ask the user questions and stop, waiting for the user to enter some input.

Sometimes the user doesn't always want to pass in _everything_ as args when running the cli tool. Prompting the user for input is a key skill to have in your toolbag for creating polished cli tools with a nice user experience!

<br/>

## The Exercise
Create a cli tool that simply asks the user the question, "yes or no".

After the question is printed the console should hang and wait for a user input.

The question should end by displaying [y/N] with the N capitalized to signify that it is the default input if the user simply presses the enter key without typing any text.

The cli tool should read these inputs as a "yes": y, Y, yes, Yes, YES...

The cli tool should read these inputs as a "no": n, N, no, No, NO...

After the user submits a choice either "You said yes!" or "You say no..." should be printed to the console.

<br/>

## Tests
It's up to you to decide how to unit test this code.

Write an integration test that simulates sending various inputs as a response to the yes or no question and verifies that the correct output is printed to the console.
<br/>

## Skills Practiced

- Prompting the user for input

- Simulating keystroke events in integration tests

<br/>
