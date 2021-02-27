# Comparison Operators: Evaluating Conditions
- A situation can be evaluated by comparing one value in the script to what you think it might be. The resulting *Boolean* will be true or false.
- "== (equal to)"
- "=== (strict equal to)"
- "!= (is not equal to)"
- "!== (strict not equal to)"
- "> (greater than)"
- ">= (greater than or equal to)"
- "< (less than)"
- "<= (less than or equal to)"
## Logical Operators
- Comparison operators usually return values of true or false singularly. Logical operators allow for the comparison of results of more than one comparison operator.
- && (logical and)
- || (logical or)
- ! (logical not)
## Loops
- Loops check a condition. If the condition returns true, a code block runs. The condition will then be checked again and the code block will run until the condition returns false. There are three kinds of loops: For, While, Do While.
- For loops: Used when it's needed to run code a specific number of times. In a for loop the condition is usually a counter that determines how many times the loop should run.
- While loops: Used when the number of times a code block should run is unknown. The condition here can be something other than a code loop.
- Do While loops: Similar to the While loop with a key difference, it will run the statements inside the curly braces a minimum of one time even when the condition evaluates to false.
## Loop Counters
- For loops use a counter as a condition, instructing the code to run a fixed number of times. The condition is made up of three statements: Initialization, Condition, and Update.
- Initialization: declare a variable and have it set to zero. Commonly the variable is named 'i' and acts as the counter.
- Condition: It should continuously loop until the counter reaches a specific number.
- Update: Each iteration of the code in curly braces being run adds a specified number to the counter.
- Ex. (var i = 0; i < 10; i++)