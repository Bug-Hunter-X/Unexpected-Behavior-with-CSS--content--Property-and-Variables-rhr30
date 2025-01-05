# Unexpected Behavior with CSS `content` Property and Variables

This repository demonstrates an uncommon bug related to using variables within the `content` property of CSS pseudo-elements (`::before`, `::after`).  The bug arises from improperly defined or escaped variables, as well as incorrect usage of the `var()` function for CSS custom properties (variables).

## Bug Description
The core issue lies in how the browser interprets and handles variables when used to dynamically set the `content` of pseudo-elements. Incorrectly defined or missing quotes around variable values can lead to unexpected behavior, where the content is not rendered correctly or errors are produced.

## How to Reproduce
1. Clone the repository.
2. Open `bug.css` to see the example of erroneous variable usage within the `content` property.
3. Open `bugSolution.css` to see the corrected version.
4. Observe the differences in how the content is rendered in a browser.