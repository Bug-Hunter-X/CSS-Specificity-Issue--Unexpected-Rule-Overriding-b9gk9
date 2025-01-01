# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS selector specificity. The bug involves unexpected behavior when using class selectors within a more specific parent selector.

## Bug Description

The primary issue lies in the unexpected overriding of CSS rules due to selector specificity. Even when a more precise class selector is defined later and seemingly should take precedence, it's ignored if a more general selector has higher specificity. 

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic CSS code.
3. Observe that the expected 'purple' color does not apply as the selector isn't considered as specific enough.
4. Open `bugSolution.css` to see how to solve the problem. 

## Solution

The solution involves understanding and correctly applying CSS specificity rules. Refer to `bugSolution.css` for a fix.