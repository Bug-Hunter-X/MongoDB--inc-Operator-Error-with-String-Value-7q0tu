# MongoDB $inc Operator Error with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries: attempting to increment a field by a string value.

The `bug.js` file contains the incorrect code that causes the error. The `bugSolution.js` file provides the corrected code.

## Bug Description
The original code attempts to increment the 'count' field by the string value '1'. This will lead to an error because the `$inc` operator expects a numerical value.

## Solution
The solution replaces the string '1' with the numeric value 1, ensuring the `$inc` operator works as intended.