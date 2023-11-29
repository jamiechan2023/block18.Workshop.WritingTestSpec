# block18.Workshop.WritingTestSpec
## 'Multiplication' Function
### Unit test (in form of Expect [action] to be [some result])
Expect multiply(2, 3) to be a number
Expect multiply(2, 3) to be equal to 6
Expect multiply("a", 3) to be an error
Expect multiply() to be an error
Expect multiply(2) to be an error
Expect multiply(2, 3, 4) to be an error

### Unit test (in form of pseudocode/plain English)
We expect the function to:
- accept two numbers (x,y) as arguments
- multiply two numbers (x,y) together
- product = x*y
- return product

We expect error returned from the function if:
- any of the arguments is NOT numeric (i.e. strings, objects, arrays, etc.,)
- the number of arguments NOT 2 (i.e. only one argument, no arguments or more than two arguments)

## 'concatOdds' Function
### Unit test (in form of Expect [action] to be [some result])
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be a integer array
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be result in [-1, 1, 3, 9, 15]
Expect concatOdds(3, 2, 1, 9, 1, 1, 1, 4, 15, -1) to be an error
Expect concatOdds(["a", 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an error
Expect concatOdds() to be an error
Expect concatOdds([3, 2, 1]) to be an error
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1], [1,2,3]) to be an error

### Unit test (in form of pseudocode/plain English)
We expect the function to:
- accept two arrays of integer ([int1,int2,int3...],[inta,intb,intc...]) as arguments
- concatenate the odd numbers from the two arrays 
- return a new array with only the odd numbers concatenated from the two arrays
- return a new array with NO duplicate values 

We expect error returned from the function if:
- any of the arguments is NOT an array 
- any of the elements in the pass in array is NOT numeric (i.e. string, object, etc.)
- the number of arguments NOT 2 (i.e. only one argument, no arguments or more than two arguments)

## Shopping cart feature
### Function test 
1. when a user clicks "Checkout" as guest, they should be asked if they want to create an account or log in
2. if user want to continue checkout as guest, they should be allowed to proceed
3. if user click "Log In" and has filled in their login and password correctly, they should be taken to the shopping cart page
4. if user click "Create Accoun
    
5. when a user checkout an emtpy shopping cart, they should be shown an error
6. when a user clicks "Checkout" , a page listing all the purchase items, their quantities, the total amount and a "Next" button for user to proceed to next page for delivery details
7. when a user clicks "Next", a page for user to input delivery details
8. when a user clicks "" 
     




