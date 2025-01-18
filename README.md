# Unexpected Array Input to TypeScript Function

This example demonstrates a common error in TypeScript when dealing with function arguments. The `greeter` function expects a string, but an array is passed as an argument, resulting in a runtime error. The solution involves type checking and handling of potential errors.

## Bug
The `bug.ts` file contains the function `greeter` which expects a single string argument, however it is passed an array of strings, leading to a runtime error.