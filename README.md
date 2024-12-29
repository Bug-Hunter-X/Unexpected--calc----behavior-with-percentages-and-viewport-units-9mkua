# Unexpected calc() Behavior with Percentages and Viewport Units

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when combining percentages and viewport units (like `vw` or `vh`).  The expected calculation does not match the rendered output in certain browsers.

## Bug Description

The `calc()` function, when used with a combination of percentages and viewport units, may yield inaccurate results. This inconsistency can lead to layout issues and unexpected visual differences across browsers.

## Reproduction Steps

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected layout due to the incorrect `calc()` calculation.

## Solution

The solution involves understanding the calculation order and potential browser inconsistencies.  A workaround might involve using alternative methods such as JavaScript or pre-calculating the values based on viewport size.