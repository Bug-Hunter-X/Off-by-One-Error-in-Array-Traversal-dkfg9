# Off-by-One Error in Java Array Traversal

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= arr.length` attempts to access an element beyond the valid index range of the array, leading to an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the buggy code. The `bugSolution.java` file provides the corrected version.

This example highlights the importance of carefully checking loop conditions when working with arrays in Java and other programming languages.