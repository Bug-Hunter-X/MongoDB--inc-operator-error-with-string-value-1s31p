# MongoDB $inc operator error with string value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value. Attempting to increment with a string will result in an error or unexpected behavior.

## Bug Description
The bug arises from providing a string value to the `$inc` operator, which expects a number. This leads to an error or inaccurate update.

## Solution
The solution is straightforward: ensure that the value being incremented with `$inc` is a valid number.