# block18.Workshop.WritingTestSpec
## 'Multiplication' Function
### Unit test (in form of Expect [action] to be [some result])
- Expect multiply(2, 3) to be a number
- Expect multiply(2, 3) to be equal to 6
- Expect multiply("a", 3) to be an error
- Expect multiply() to be an error
- Expect multiply(2) to be an error
- Expect multiply(2, 3, 4) to be an error

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
- Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be a integer array
- Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be result in [-1, 1, 3, 9, 15]
- Expect concatOdds(3, 2, 1, 9, 1, 1, 1, 4, 15, -1) to be an error
- Expect concatOdds(["a", 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an error
- Expect concatOdds() to be an error
- Expect concatOdds([3, 2, 1]) to be an error
- Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1], [1,2,3]) to be an error

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
2. if a user continue to checkout as guest, they should be allowed to proceed
3. if a user clicks "Log In" but has filled out an incorrect login or password, they should be shown an error and prompted to sign up if they have not yet
4. if a user clicks "Log In" and has filled in their login and password correctly, they should be taken to the main page
5. if a user clicks "Create Account" with an invalid email address or password, they should be shown an error
6. if a user clicks "Create Account" and has filled in all the required information correctly, they should receive an email for account activation
7. when a user checkout an emtpy shopping cart, they should be shown an error
8. when a user clicks "Checkout", they should be taken to the Purchase detail page which will show all the purchase items, their quantities, tax and/or charges, the total amount and a "Confirm" button for user to confirm the purchase details 
9. when a user clicks "Confirm" on the Purchase detail page, they should be taken to the next step for checkout which is the Shipping detail page
10. when a user clicks "Next" on the Shipping detail page but has not fill out all the required shipping information, they should be prompted to input the missing details
11. when a user clicks "Next" on the Shipping detail page and has filled out all the required shipping information, they should be shown the final total amount which include the shipping fee
12. when a user clicks "Next" on the Final total amount page, they should be taken to the next step for checkout which is the Payment detail page
13. when a user clicks "Complete" on the Payment detail page but has not fill out all the payment information, they should be prompted to input the missing details
14. when a user clicks "Complete" on the Payment detail page and has filled in all required payment information, they should be taken through the authentication process of the payment method they select
15. when completed the authentication process of payment, they should be taken to the order confirmation page which will show a Order reference number
     




