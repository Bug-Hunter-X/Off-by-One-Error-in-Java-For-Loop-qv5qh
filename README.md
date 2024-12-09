# Off-by-One Error in Java

This repository demonstrates a common off-by-one error in Java and provides a solution.

The `Bug.java` file contains code with an error that leads to an `ArrayIndexOutOfBoundsException`. The `BugSolution.java` file provides the corrected version of the code.

## Bug Description
The bug lies in the `for` loop. The loop condition `i <= arr.length` is incorrect, it should be `i < arr.length` to avoid accessing an element outside the array bounds.

## Solution
The solution involves correcting the loop condition to `i < arr.length`, ensuring that the loop iterates only within the valid indices of the array.