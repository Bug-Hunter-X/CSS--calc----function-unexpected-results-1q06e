# CSS `calc()` Function Unexpected Results
This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to incorrect unit handling or operator precedence.

The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected version.

## Bug Description
The `calc()` function in CSS allows for dynamic calculation of lengths and other CSS values. However, it is crucial to use correct units for all operands and to be mindful of operator precedence to achieve expected outcomes.  Using `calc()` with properties incompatible with percentages can also lead to unexpected results.

## Solution
The corrected code in `bugSolution.css` addresses the issues by ensuring consistent units and correct order of operations within the `calc()` function.  It also ensures compatible usage with the specific CSS properties.
