# Inconsistent Layout with Floats and Percentages in CSS

This repository demonstrates a common layout issue encountered when using floats and percentages in CSS.  Some browsers handle the combination inconsistently, leading to unexpected rendering behavior.

## Bug Description
The CSS code in `bug.css` attempts to create a two-column layout using `float: left;` and `width: 50%;`.  However, this can produce inconsistent results across different browsers or when the parent container's width isn't explicitly defined.

## Solution
The solution, found in `bugSolution.css`, addresses this by employing more robust layout techniques that provide greater cross-browser consistency.  This solution shows how to solve the problem.