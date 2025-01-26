# Java Off-by-One Error Example

This repository demonstrates a common off-by-one error in Java that leads to an `ArrayIndexOutOfBoundsException`.  The error occurs in a simple loop iterating over an array. The corrected version demonstrates how to avoid this error.

## Bug

The `bug.java` file contains the buggy code. The loop attempts to access an array element beyond the array's bounds. 

## Solution

The `bugSolution.java` file provides a corrected version where the loop condition prevents accessing an invalid index.