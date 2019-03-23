### Constants 
Go supports constants of character, string, boolean, and numeric values.

const declares a constant value.

We can define const anywhere a var statement can.
Constant expressions perform arithmetic with arbitrary precision.
A numeric constant has no type until it’s given one, such as by an explicit cast.

A number can be given a type by using it in a context that requires one, such as a variable assignment or function call. For example, here math.Sin expects a float64.

### If-Else
You don't need to put parantheses around conditions in Go, but braces
are required

There is ternary if in Go, so you'll need to use a full if statement even
for basic conditions

### Switch 
You can use commas to seperate multiple expressions in the same case 
statement. We use the optional default case in this example as well.

switch without an expression is an alternate way to express way if/else 
logic. Here we show how the case expressions can be non-constants.

A type switch compares types instead of values. 