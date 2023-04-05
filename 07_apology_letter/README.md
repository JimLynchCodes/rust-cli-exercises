# Arg Parse
Build a cli tool that generates apology letters!

<br/>

## Backstory
Imagine you are the PR person for some loose cannon celebrity. You often have to write letters apologizing to those in the wake of your client's craziness so you decide to write a little cli tool that will generate apology letters.

<br/>

## The Exercise
This cli tool should take two positional arguments:

1) recipient name - the name of the person you are apologizing to.

2) thing you did - the act that we are apologizing for.

The program should read in the file "example_input.txt", replace the placeholders with the supplied args, and then write the output to a text file in the "output" folder.

<br/>

## Tests
Try to extract the string replacing logic into pure functions with unit tests.

Create an integration test that actually recreates and saves the output file and asserts that is has the exact same contents as the expected output file in the "expected" directory.
<br/>

## Skills Practiced

- Reading and writing text files

- Splitting and joining strings

- Reading positional args 

<br/>
