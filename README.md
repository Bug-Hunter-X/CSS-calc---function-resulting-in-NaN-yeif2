# CSS calc() NaN Bug
This repository demonstrates a common error encountered when using the CSS `calc()` function: generating `NaN` (Not a Number) due to incompatible unit operations.

The `bug.css` file contains the erroneous code, resulting in unexpected layout. The solution is provided in `bugSolution.css`.

## Reproducing the Bug
1. Open `bug.html` in your browser.
2. Observe the unexpected layout caused by the `NaN` value generated by the `calc()` function.

## Solution
The `bugSolution.css` file demonstrates how to correct the unit handling within the `calc()` function to avoid the `NaN` error. The solution typically involves ensuring that all parts of the calculation use compatible units or converting units as needed.

This demonstrates a crucial aspect of CSS unit handling and the importance of careful consideration when working with calculations.