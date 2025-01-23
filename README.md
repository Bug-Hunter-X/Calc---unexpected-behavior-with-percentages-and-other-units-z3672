# CSS calc() unexpected behavior

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  The issue arises when combining percentages and other units within the `calc()` expression, leading to inconsistent rendering across different browsers. 

The `bug.css` file shows the problematic code. The `bugSolution.css` provides a potential fix by ensuring proper unit handling or providing alternative layout solutions.

This bug highlights the need to carefully manage units when using `calc()` to ensure consistent rendering across browsers.  Thorough testing across different environments is recommended to catch such issues early.