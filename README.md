# CSS calc() Function Error

This repository demonstrates a common yet subtle error when using the `calc()` function in CSS, specifically the necessity of spaces around arithmetic operators, and the issue of potentially negative calculated widths.

## Bug
The `bug.css` file contains an incorrect use of the `calc()` function. The missing space around the `-` operator leads to unexpected results in various browsers.

## Solution
The `bugSolution.css` file presents the corrected version, showing the proper spacing and addressing the possibility of negative widths through conditional logic or alternative calculation methods.

## How to reproduce
1. Clone the repository.
2. Open `bug.html` in a web browser to observe the incorrect rendering due to the erroneous `calc()` function.
3. Then open `bugSolution.html` to see the corrected output.