# ApplyBind-Curry-functions
Curry functions developed using the JavaScript Apply and Bind function methods.

The repository contains the primary products from my article entitled "Curry in a Bind" on the [MoaPWAD](https://gilmoretj.wordpress.com/personal-projects/curry-in-a-bind/) blog site.

## Apply solution
There are three files implemented using the `apply()` method of the function object.

* Defined number of Arguments
* Undefined number of Arguments
* Combined solution handles both of the above.

This approach permits the supply of more than one argument at a time but retains them inside the curried function as internal data.

## Bind solution
There are three files implemented using the `bind()` method of the function object.

* Defined number of Arguments
* Undefined number of Arguments
* Combined solution handles both of the above.

This approach insists in having the arguments supplied one at a time and retains them within the call stack of the curried function.

Neither of the above approaches use the `apply` or `bind` functions as OO methods; the context argument is of no consequence.
