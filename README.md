# Type 'string[]' is not assignable to type 'string'

This repository demonstrates a common TypeScript error: passing an array to a function expecting a string.

The `bug.ts` file contains the erroneous code. The `bugSolution.ts` file provides a corrected version.

## Bug

The function `greeter` expects a string argument, but an array of strings is passed. This results in a type error.

## Solution

The solution involves either changing the function signature to accept an array or modifying the call site to pass a single string.