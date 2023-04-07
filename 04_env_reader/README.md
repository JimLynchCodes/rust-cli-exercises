# Env Reader
Build a cli tool that reads and prints environment variables!

<br/>

## Backstory
Imagine you want to build a cli tool that uses some secret keys or credentials. It's a _huge_ no-no to hardcode them right into your project and save them into source control.

Instead, you should probably load in these secrets as _environment variables._

<br/>

## The Exercise
The goal here is to read the environment variables in two different ways.

The first variable should be named `MY_VAR_1=hello!!` and should be read from a .env file.

The second variable should be named `MY_VAR_2` and should _not_ be declared in the .env file and instead should be exported in the same shell that the program is run. If MY_VAR_2 is not exported, use the string `"default val"` as the default value.

The values of both variables should be printed to the console.

<br/>

## Tests
It's up to you to decide if / how you would unit test this.

Write at least one integration test that verifies the correct values were printed to the console.

<br/>

## Skills Practiced

- Reading environment variables from a .env file

- Reading environment variables from the current execution environment

<br/>
