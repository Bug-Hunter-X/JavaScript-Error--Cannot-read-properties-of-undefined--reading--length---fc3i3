# JavaScript Bug: Handling Undefined 'length' Property

This repository demonstrates a common JavaScript error and its solution. The error occurs when attempting to access the `length` property of a variable that is not an object with a `length` property (e.g., a number or undefined).  The solution showcases how to gracefully handle such scenarios using proper type checking and null handling.

## Bug Description

The `foo` function attempts to return the length of its argument.  If the argument is not an object with a length property, the code throws a `TypeError: Cannot read properties of undefined (reading 'length')`.

## Solution

The solution incorporates checks to ensure the argument is an object and has a `length` property before attempting to access it.  This prevents the error and handles various input types gracefully.
