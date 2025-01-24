# Python Bug: Average Calculation with Zeros and Empty Lists
This repository demonstrates an uncommon bug in Python related to calculating the average of a list of numbers that might include zeros or be empty.  The original code has a flaw in its handling of these edge cases.
The `bug.py` file shows the code with the bug. The `bugSolution.py` file offers a corrected version that avoids the problem.
## Bug Description
The primary issue is the potential for `ZeroDivisionError` if the input list is empty and for inaccurate results when the list contains zeros.
## Solution
The solution involves adding checks to handle empty lists and lists containing only zeros gracefully.  This improves the robustness of the function.