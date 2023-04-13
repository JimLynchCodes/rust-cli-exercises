# Pizza Order
Create a cli tool that orders pizzas!

<br/>

## Backstory
Imagine you are in charge ordering for a massive organization that has no pizza oven.

You decide to make a cli tool to make ordering the pizzas faster and easier!

<br/>

## The Exercise
Because we sometimes order things other than pizza, let's make the literal string `pizza` the first positional argument for these pizza ordering situations, and this should be a required argument.

Then we can take the other information flags for our cli tool:

- Size, --size or -s flags, possible values are: "small (s), medium (m), large (l), or xtra large (xl)"

    -> If the user does not pass the size flag, prompt for a size with a "select" input.

- Toppings, --toppings or -t flag, possible values are: "Pepperoni, Sausage, Mushrooms, Bacon, Onions, Extra Cheese, Peppers, Chicken, Pineapple"

    -> If the user does not pass the size flag, prompt for a size with a "multiselect" input. Up to two toppings can be chosen, and no toppings selected should also be a valid choice.

- Room Number, --room or -r flag, possible values are strings of the form "XYYY" where "X" is the department letter ("A", "B", "C", "D", or "E") and the X is the room number, which can be any 1, 2, or three digit positive number (excluding zero).

- Quantity, --quantity or -q flag, possible values are integers between 1 and 25. If this flag is not present, do not prompt user for it. Instead, just assume quantity of 1.

- Confirm, --confirm or -c flag, doesn't take any value argument. If this flag is NOT passed, read the order back after collecting other information and prompt user for Y/n confirmation. If the flag is present, skip this prompt.


After the cli tool collects all information and confirms it should print out, "Your order for [quantity] [size] [toppings] pizza(s), delivered to [room], has been placed!"

<br/>

## Skills Practiced

- Parsing command line args and flags

- Prompting the user with text, y/n confirm, select, and multiselect inputs.

- Handling default argument values.

- String and number input validation.

- Conditionally prompting the user _only if_ flag is not present (a common thing in real world cli tools!) 

<br/>

## Bonus

- Support _both_ args / flags inputs _and_ q/a components- prompt use to interactively enter required information not provided via args or flags. 

- Allow input to optionally be read from a text file to make things even easier for the user 

- Connect to an email or texting sending service and _actually_ place an order with a pizza shop!
