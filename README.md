# MongoDB $inc operator error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numeric field by a specified value. However, in this example, the value provided to the `$inc` operator is a string, leading to an error.

## Bug
The `bug.js` file contains code that attempts to increment the `count` field of a document in a MongoDB collection using the `$inc` operator with a string value. This results in an error because the `$inc` operator only works with numbers.

## Solution
The `bugSolution.js` file provides the corrected code. The value provided to the `$inc` operator is changed to a number, resulting in the correct increment of the `count` field.
