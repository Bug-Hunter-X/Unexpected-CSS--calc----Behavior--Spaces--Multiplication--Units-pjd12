# Unexpected CSS `calc()` Behavior
This repository demonstrates common, yet uncommonly caught, errors when using the `calc()` function in CSS.  These errors stem from incorrect spacing, missing multiplication operators, and unit mismatches.

The `bug.css` file showcases these issues.  The `bugSolution.css` file provides the corrected versions.

## Issues:
* **Missing Spaces:** Spaces are crucial within `calc()` expressions.  Omitting them leads to parsing errors.
* **Missing Multiplication Operators:**  Implicit multiplication is not supported; explicit `*` is necessary.
* **Unit Mismatches:** While some unit combinations work (e.g., px + %), others lead to unpredictable results.

This is a demonstration of subtle errors that can be easily missed, causing significant layout problems.