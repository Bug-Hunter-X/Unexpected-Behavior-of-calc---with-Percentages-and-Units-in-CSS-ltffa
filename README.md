# Unexpected Behavior of calc() with Percentages and Units in CSS

This repository demonstrates an uncommon bug related to the `calc()` function in CSS when dealing with percentages and other units.  The bug can lead to unexpected layout issues due to inaccurate calculations by the browser.

## Bug Description
The `calc()` function, while powerful, can produce unexpected results under specific circumstances.  This is particularly true when using a mix of percentages and fixed units like `px`, or when combining multiple percentages within a single `calc()` expression.  Browsers might interpret percentages relative to different containing elements, leading to miscalculations.

## Reproduction
The `bug.css` file demonstrates the issue.  Observe the unexpected width of the affected elements in different browser contexts and parent container sizes.

## Solution
The `bugSolution.css` file provides a solution.  This might involve using alternative units, restructuring the CSS to avoid ambiguous percentage calculations, or explicitly setting parent element dimensions to ensure accurate calculations by `calc()`.  The specific solution depends on the exact layout requirements and how the `calc()` function is being used.

## Contributing
Contributions are welcome. Feel free to submit pull requests or report additional scenarios where this bug manifests.