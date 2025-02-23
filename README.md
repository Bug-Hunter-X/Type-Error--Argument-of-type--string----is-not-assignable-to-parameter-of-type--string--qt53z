# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common type error in TypeScript and its solution.  The error arises from passing an array of strings to a function expecting a single string.

## Bug
The `bug.ts` file contains a function `greeter` that expects a string argument. However, an array of strings is passed to it, causing a type error.

## Solution
The `bugSolution.ts` file corrects the error by either modifying the `greeter` function to accept an array or changing how the array is handled to correctly pass a single string.