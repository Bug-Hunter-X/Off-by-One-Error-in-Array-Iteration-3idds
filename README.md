# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition `i <= arr.length` allows the loop to access an index that is out of bounds, resulting in an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the code with the error. The `bugSolution.java` file provides the corrected version.

This example highlights the importance of carefully considering array indices when iterating.  Always ensure that your loop conditions correctly handle the bounds of the array to prevent runtime errors.