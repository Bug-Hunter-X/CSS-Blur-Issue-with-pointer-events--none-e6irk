# CSS Blur Issue with `pointer-events: none`

This repository demonstrates a bug where applying the `filter: blur()` CSS property to an element with `pointer-events: none` results in an unexpected or incorrect rendering of the blur effect.  The issue is inconsistent across different browsers.

The `bug.css` file contains the problematic CSS code. The `solution.css` file offers a potential workaround.

This bug is particularly relevant when dealing with elements that should not receive mouse events but still need a visual blur effect, such as a background element or overlay.