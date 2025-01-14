# CSS `calc()` Pitfalls

This repository demonstrates some less-obvious issues that can arise when using the `calc()` function in CSS.  It includes examples of unexpected behavior due to operator precedence, unit handling inconsistencies across browsers, and performance problems from deeply nested `calc()` expressions. The `bug.css` file shows these problems, and `bugSolution.css` offers improved, more robust alternatives.

## Issues Addressed

* **Operator Precedence:**  Incorrect order of operations within `calc()` can lead to incorrect calculations. Proper use of parentheses is crucial.
* **Unit Inconsistency:**  Mixing percentages, pixels, ems, etc., within a single `calc()` expression can cause unexpected results in certain browsers. Careful unit selection and usage is key.
* **Deep Nesting:** Overly complex and nested `calc()` expressions can impact rendering performance.  Simpler alternatives may be preferred.
