# Traveling Salesman
Create a cli tool that finds the shortest route for the traveling salesman to take!

<br/>

## Backstory
Let's suppose this map represents the world you live in, and you are the traveling salesman. You begin at one city with all your inventory. Then you visit each city to sell your items and in the end you return home.

<br/>

example visualization:
<img src="./traveling_salesman_problem.png">

<br/>

To go from any one city to another has a cost (think of it as the amount of gasoline used, or hours traveled, etc). The goal is to write a function that takes:

<br/>

1) the city you need to begin and end with, and

<br/>
 
2) this matrix of costs for traveling between cities.

<br/>


## The Exercise

Part of the challenge here is determining how to represent the data in the visualization in terms of Rust data types.

The cli tool should accept two arguments: 

<br/>
1) in the information about distances from one city to another, and

1) The starting/ending city.


The cli tool should output two things:

<br/>
 1) the order of cities to in the most optimal path (or paths), and 
 
<br/>
 2) the total travel cost of the entire path. Good luck! ⭐️

<br/>

## Tests
Unit test the pure logic, number crunching functions here.

Once you find the optimal route, create an integration test that asserts the correct route and length is calculated!  

<br/>

## Skills Practiced

- Working with weighted node/edge style graphs

- Deciding how to structure abstract data
  
<br/>

## Bonus

- Provide also the "second best route"

- If there are multiple routes tied for the best, print all of them

- Provide a nice error message if given a starting/ending city that is not in the distance data
