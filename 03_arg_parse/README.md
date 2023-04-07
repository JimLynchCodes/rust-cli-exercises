# Arg Parse
Build a cli tool that reads and prints arguments!

<br/>

## Backstory
Imagine you want to build a cli tool. Well, if you want the user to be able to send some parameter or input as they run it... those are what we call _arguments._ 

<br/>

## The Exercise
Write a Rust program that takes two string arguments.

The first argument should be required (the program errors or panics if it is not supplied with `cargo run`).

The second argument is optional- if it is not supplied the program continues successfully, and arg2 is set to the `None` Option variant.

Also, the cli tool should accept an optional flag. The flag can be passed as the long version `--flag` or the short version `-f`, and the flag take a positive integer as a parameter. The cli tool should print the number to the console, or just "None" if called without the flag.

If both arguments are passed with `cargo run` then both are printed to the console.

Additional arguments are ignored (or cause an error, up to you).

<br/>

## Tests
It's up to you to decide if / how you would unit test this.

There are a few integration tests you can write, where the test code more or less calls `cargo run`, passing in a different number of args for each test, and then expecting the proper text to be printed to the console or panicking to occur. 

<br/>

## Skills Practiced

- Reading positional cli arguments

- creating required and optional args

- Flags with a short and long name

- Flags that take a parameter

<br/>

## Bonus

Bonus points for finding multiple different ways of implementing this!
