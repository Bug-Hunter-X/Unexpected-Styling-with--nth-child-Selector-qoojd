# Unexpected Styling with CSS :nth-child Selector

This repository demonstrates a common CSS issue related to the `:nth-child` pseudo-class. The `bug.css` file contains code that incorrectly styles only even-numbered children within a container. This can lead to unexpected visual results if a different pattern is required.  The solution, shown in `bugSolution.css`, provides a more accurate way to achieve the desired styling.

## Problem
The original CSS unintentionally selects only even children. If you need to select other children, a different formula is needed.  Consider using a more precise selector or adjusting the parameters of `:nth-child`.