# Bin Files
Create a cli tool where the logic is split out nicely into separate functions and files. 

<br/>

## Backstory
Imagine you want to make a cli tool that ultimately builds into a single binary executable file but depends on lots of different functions.

The idea is that this code can serve as a proof-of-concept for a medium to large-scale codebase all contained within a single binary project.

<br/>

## The Exercise
The exercise is to create three functions in three separate files, all called from `main` which should print the total sum of the three numbers returned by `fn1`, `fn2`, and `fn3`.

1) The first function should be named `fn1` and should live inside a module named `mod1`. This function should just return the number 1. 

2) The second function should be named `fn2` and should live inside a module named `mod2`. This module should import `f1` from `mod1`, and `fn2` should return 2 times the result of calling `fn1`.

3) The third function should be named `fn3` and should live inside a module named `mod3` (which itself may or may not live inside of other modules). This file should be inside of a subfolder and not next to the main.rs file, and it should return the number 3 when called.

<br/>

## Tests
The unit tests for fn1 and fn3 should check that they return the proper values. Experiment with returning a mocked value of fn1 when calling the fn2 unit test.

As an integration test, verify that the grand total of 6 is printed to the console.

<br/>

## Skills Practiced

- Creating helper functions and modules

- Importing a helper function and module in main.rs

- Importing a helper function and module into another helper function and module

- Importing a helper function and module from a subfolder

<br/>
