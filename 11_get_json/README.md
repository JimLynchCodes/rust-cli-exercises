# Get Json
Create a cli tool that gets some json! 

<br/>

## Backstory
Imagine you want to make a cli tool that brings in some outside data!

This cli tool is a proof-of-concept for a whole class of cli tools that can make all the REST api calls you could ever imagine!

<br/>

## The Exercise
The exercise is to write a cli tool that calls out to and endpoint, gets some json, and parses it into data that Rust understands.

Use the endpoint here as the source for your json data: https://jsonplaceholder.typicode.com/users/1

Then print the "name" field from the json data to the console.

<br/>

## Tests
It's up to you to decide how you would unit test this code.

Write a unit test that calls out the endpoint and expects the correct text to be printed to the console.

<br/>

## Skills Practiced

- Making a GET request

- Parsing JSON data

<br/>

## Bonus

Try two different ways of parsing the json: one by deserializing it to a defined struct and one where you work with it as a dynamic value blob of data!