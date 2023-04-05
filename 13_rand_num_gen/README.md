# Random Number Generator
Create a cli tool that generates random numbers!

<br/>

## Backstory
Imagine you want to make a cli tool is not totally deterministic but rather incoporates some element of randomness to spice things up!

The idea is that this code can serve as a proof-of-concept any Rust project where want to generate some random integer or floating point number.

<br/>

## The Exercise
The exercise is to create two functions, one that makes random integer numbers and one that makes random float numbers.

The integer function should take a lower bound and an upper bound, and the generated number should be between these bounds. 

The float function should generate a random floating point number between zero and one.

BOTH functions should take a parameter that controls whether the lower and higher bounds are _inclusive_ or _exclusive_ bounds.

There are four options:

- include both: both the lower and upper bound are valid values for the generated number

- exlude both: neither the lower nor upper bound can be chosen as the generated random number

- include left: exclude right - only the lower bound can be chosen as the generated number

- exclude left: include right - only the higher bound can be chosen as the generated number

Print the generated random numbers to the console.

<br/>

## Tests
It's up to you to decide how you would unit test this code.

Write some integration tests that generate a few random numbers and verify that they are within the proper bounds.
<br/>

## Skills Practiced

- Generating random integer and float numbers

<br/>
