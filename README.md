# Python Average Calculation Bug

This repository demonstrates a common error in Python: a `ZeroDivisionError` that can occur when calculating the average of an empty list. The `calculate_average` function is designed to handle this scenario gracefully.

## Bug Description

The `calculate_average` function in `bug.py` fails when an empty list is passed as input. This is because `len(numbers)` returns 0, leading to a division by zero.  The solution in `bugSolution.py` addresses this issue by explicitly checking for an empty list and returning 0 as the average in such cases.

## Solution

The `bugSolution.py` file contains a corrected version of the `calculate_average` function.  It adds a conditional statement to check if the list is empty before performing the division, thus avoiding the `ZeroDivisionError`.

This example highlights the importance of robust error handling in Python to prevent unexpected crashes.