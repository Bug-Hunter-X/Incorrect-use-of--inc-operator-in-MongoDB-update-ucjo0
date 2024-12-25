# Incorrect Use of $inc Operator in MongoDB Update
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB update operations.  The issue arises from providing a string value instead of a numeric value to the `$inc` operator. This results in unexpected behavior and may lead to data inconsistencies.

## Bug
The `$inc` operator is designed to increment a numeric field by a specified value. However, attempting to increment it with a string will not work as intended.

## Solution
The solution involves ensuring that the value used with `$inc` is a valid number (integer or float) to achieve the desired increment operation.
