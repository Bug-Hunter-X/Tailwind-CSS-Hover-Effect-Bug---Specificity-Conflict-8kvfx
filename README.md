# Tailwind CSS Hover Effect Bug

This repository demonstrates a bug related to the hover effect in Tailwind CSS. The issue involves an unexpected behavior of the hover pseudo-class selector, likely caused by specificity issues or an interaction with other CSS rules.

## Bug Description

A hover effect on an element is not applying correctly as expected.  This can manifest in various ways, such as the hover styles not showing up at all, only partially applying, or conflicting with other styles.

## Reproduction
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Hover over the paragraph; the expected hover style is not applied.

## Solution
The solution involves addressing the specificity conflict or other CSS interaction that's preventing the hover effect from working as expected.  This might include using !important (use with caution) or adjusting the specificity of the conflicting CSS rules.

See `bugSolution.js` for the corrected code.