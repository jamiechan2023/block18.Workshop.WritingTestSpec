# block18.Workshop.WritingTestSpec

Expect multiply(2, 3) to be a number
Expect multiply(2, 3) to be equal to 6
Expect multiply("a", 3) to be an error
Expect multiply() to be an error
Expect multiply(2) to be an error
Expect multiply(2, 3, 4) to be an error

We expect the function to:
- accept two numbers (x,y) as arguments
- multiply two numbers (x,y) together
- product = x*y
- return product

We expect error returned from the function if:
- if any of the arguments is NOT numeric (i.e. strings, objects, arrays, etc.,)
- if the number of arguments NOT 2 (i.e. only one argument, no arguments or more than two arguments)
