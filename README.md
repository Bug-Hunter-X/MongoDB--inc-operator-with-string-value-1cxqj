# MongoDB $inc operator with string value

This example demonstrates an incorrect use of the `$inc` operator in a MongoDB update operation. The `$inc` operator is designed to increment or decrement a numerical value. In this example, however, it attempts to increment a field with a string value, resulting in an unexpected behavior or error.

## Bug
The `bug.js` file contains the faulty code which uses `$inc` operator incorrectly.

## Solution
The `bugSolution.js` file provides the corrected code, ensuring a numerical value is used with `$inc` operator to update the field correctly.
