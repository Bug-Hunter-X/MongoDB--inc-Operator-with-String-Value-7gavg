# MongoDB $inc Operator with String Value

This example demonstrates an incorrect usage of the MongoDB `$inc` operator, where a string is used instead of a number.  The `$inc` operator is designed to increment a numeric field. Using a string leads to an unexpected outcome where the field is not incremented as intended.

## Bug
The `bug.js` file shows the incorrect implementation.  The solution is provided in `bugSolution.js`.

## Solution
The solution corrects the usage of the `$inc` operator by ensuring a numeric value is provided for the increment.