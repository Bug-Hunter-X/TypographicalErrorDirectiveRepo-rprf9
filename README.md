# Tailwind CSS @apply Directive Error

This repository demonstrates an uncommon error in Tailwind CSS involving the `@apply` directive.  The error occurs when attempting to apply a class that either doesn't exist within your Tailwind CSS configuration or contains a typo.

## Bug

The `bug.html` file contains a simple example of this error. The `@apply` directive references a non-existent class. This leads to no styling applied from the `@apply` directive, meaning only `bg-red-500` will be applied.

## Solution

The `bugSolution.html` file demonstrates the solution.  Ensure that all classes used with `@apply` are valid Tailwind CSS utility classes and correctly typed.