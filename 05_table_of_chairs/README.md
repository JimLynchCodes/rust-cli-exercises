# Table of Chairs
Create a cli tool that prints data in a nice tabular format!

<br/>

## Backstory
Imagine you are the officer manager for, and have a to buy lots of chairs. You would like to view the data in a nice spreadsheet-like table rather than just a blob of json.

This code can serve as a proof-of-concept for any cli-tool that needs to output a lot of data in a visually appealing format with nice rows, columns, and column headers. 

<br/>

## The Exercise
The exercise is to visually display chair data in a nice table so that it looks something like this:

```
+--------------------------------+---------+-----------+----------+
| Name                           | Price   | Color     | Quantity |
+--------------------------------+---------+-----------+----------+
| Ergonomic Office Chair         | $199.99 |   Black   |       20 |
+--------------------------------+---------+-----------+----------+
| Bucket Seat Gaming Chair       | $249.99 | Turquoise |        3 |
+--------------------------------+---------+-----------+----------+
| Curl Swivel Accent Chair       | $407.96 |  Orange   |        2 |
+--------------------------------+---------+-----------+----------+
| Velvet High Back Rocking Chair | $113.99 |   Blue    |        1 |
+--------------------------------+---------+-----------+----------+
| Velvet High Back Rocking Chair | $27.99  |   Grey    |        5 |
+--------------------------------+---------+-----------+----------+"
```

Feel free to hardcode the chair data as structs, arrays, or vectors.

<br/>

## Tests
It's up to you to decide how you would unit test this code.

Write some integration tests that verify that the console output contains the correct data, nicely displayed in a tabular format.
<br/>

## Skills Practiced

- Displaying data in the terminal console as a table

<br/>
