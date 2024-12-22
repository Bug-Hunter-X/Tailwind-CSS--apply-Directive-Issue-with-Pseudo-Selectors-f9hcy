# Tailwind CSS @apply Directive Issue with Pseudo-Selectors

This repository demonstrates a bug where Tailwind CSS's `@apply` directive doesn't correctly apply styles when used with pseudo-selectors like `:hover` or `:focus`. 

## Bug Description
The `@apply` directive is intended to apply the styles of a pre-defined class to another class. However, when the applied class includes pseudo-selectors, the styles aren't applied in the expected way. 

## Bug Reproduction
1. Clone this repository.
2. Open `bug.css` and `index.html` files.
3. Observe that the hover and focus styles are not applied correctly.

## Solution
The solution is to move the pseudo-selector styles outside the `@apply` directive. 

## Solution Reproduction
1. Open `bugSolution.css` and `index.html` files.
2. Observe that the hover and focus styles are now applied correctly.
