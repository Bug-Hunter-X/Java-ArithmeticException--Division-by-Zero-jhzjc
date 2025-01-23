# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` caused by division by zero.  The `bug.java` file contains the erroneous code, while `bugSolution.java` provides a solution to prevent the exception.

**Problem:**
The original code attempts to divide an integer by zero, which is mathematically undefined and leads to an `ArithmeticException`.

**Solution:**
The solution involves adding error handling to check if the divisor is zero before performing the division.  This prevents the exception and allows for graceful handling of the situation (in this case, printing an error message).

This example highlights the importance of defensive programming and handling potential runtime exceptions in your Java applications.