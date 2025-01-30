# JavaScript Null vs. Undefined Handling in Addition

This repository demonstrates a common, yet subtle, bug in JavaScript related to how it handles null or undefined values in arithmetic operations.  The initial code only explicitly checks for null values, leading to unexpected errors when undefined values are encountered. The solution provides a more robust approach.

## Bug

The `bug.js` file contains a function that attempts to add two numbers together. It includes a check to handle null values, but fails to handle undefined values appropriately.

## Solution

The `bugSolution.js` file addresses the bug by using a more comprehensive null and undefined check, ensuring that the code behaves correctly regardless of whether the input values are null or undefined. 

## How to run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run both files to compare the results and observe how the solution addresses the bug.