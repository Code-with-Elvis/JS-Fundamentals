print JavaScript is amazing text
print 3 lines: "C is fun", "Python is cool", "JavaScript is amazing"
Add Node.js script that prints a message based on the number of command-line arguments passed to it.
This Node.js script prints the first argument passed to it.

- If **no argument** is provided, it prints: `No argument`
- Otherwise, it prints the **first argument**

It uses `console.log(...)` for output and avoids both `var` and `.length`.

This Node.js script prints two arguments in the format: <first argument> is <second argument>

- Uses `console.log(...)` for output
- Does not use `var`

This script prints `My number: <integer>` if the argument is a valid number (floats are truncated).  
If not, it prints `Not a number`.

- Uses `console.log(...)` only
- No `var` or `try/catch`

This script prints 3 predefined lines using an array and a loop:

- C is fun
- Python is cool
- JavaScript is amazing

- Uses a loop to print
- No `var` or `if/else`
- Uses `console.log(...)` only

This script prints "C is fun" a number of times equal to the first argument passed.

- If the argument is not a valid integer, it prints: `Missing number of occurrences`
- Uses a loop and no `var`
- Only uses `console.log(...)` twice

This script prints a square of "X" characters with size defined by the first argument.

- If the argument isn't a valid integer, it prints: `Missing size`
- Uses a loop and string `.repeat()` to build each line
- No `var` used, only `console.log(...)` for output

This script adds two numbers passed as arguments using a defined `add(a, b)` function.

- Prints `NaN` if one or both arguments are missing or not valid numbers
- Uses `console.log(...)` for output
- No use of `var`

This script computes and prints the factorial of an integer using recursion.

- If no valid number is passed, it returns 1 (Factorial of NaN = 1)
- Uses a recursive function
- Uses `console.log(...)` for output only
- No use of `var`
