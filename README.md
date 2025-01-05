# Null Value Handling in foo Function

This repository demonstrates a common JavaScript bug related to null value handling and its solution.

## Bug Description

The `foo` function exhibits unexpected behavior when null values are passed as arguments.  The expected behavior might vary depending on the intended functionality, but the current implementation lacks robust null handling.

## Solution

The solution involves explicitly checking for null values and handling them appropriately.  This can involve returning a default value, throwing an error, or taking another appropriate action.

## How to reproduce
1. Clone this repository
2. Open the bug.js file to observe the buggy implementation
3. Open the bugSolution.js file to see how this issue is resolved
4. Execute both js files using node to see the difference
