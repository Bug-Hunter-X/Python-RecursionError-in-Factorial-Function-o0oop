# Python RecursionError Example

This repository demonstrates a common error in recursive functions in Python: forgetting to handle edge cases that could lead to infinite recursion.

The `bug.py` file contains a factorial function that is not robust enough to handle negative input. Running this code with a negative number results in a `RecursionError`.

The `bugSolution.py` file shows the corrected version of the factorial function, handling this edge case properly.

This example highlights the importance of careful input validation and error handling when using recursion.