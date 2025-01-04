# Uncommon CSS `calc()` Error

This repository demonstrates an uncommon error related to the CSS `calc()` function.  The error occurs when the `calc()` function is used to calculate a width or height that depends on the width of the parent container, but the parent container's width is not explicitly set. This will cause the `calc()` function to not behave as expected.

Another example showcases the error if a unit is missing in the calculation.

## How to reproduce the bug:
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the unexpected behavior of the element with the class `element`.

## Solution:
The solution involves setting the width of the parent container explicitly.  Alternatively, ensure all values inside the `calc()` function have the appropriate units. The correct version of the code is in `bugSolution.css`.