# CSS Specificity Bug: !important Override

This repository demonstrates an uncommon bug related to CSS specificity and the `!important` declaration.  The `bug.css` file shows the buggy code. The unexpected behavior is that the child element's color is not red, even with the !important declaration, due to higher specificity of a more targeted selector.  The `bugSolution.css` file shows how to resolve the issue.

## Bug Description

When using `!important` within CSS, higher specificity selectors can override the rule, even if the `!important` declaration is present on a less specific selector. This is a subtle bug that may be difficult to troubleshoot.

## Solution

The solution demonstrates how to resolve this specificity conflict and achieve the intended behavior.