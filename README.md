# CSS Specificity Bug
This repository demonstrates a subtle bug related to CSS selector specificity.  The bug showcases how a seemingly innocuous style rule can override a more general rule due to the way CSS resolves conflicts.

## Bug Description
The CSS code attempts to style a container with a light blue background and its paragraph elements with blue text. However, an earlier rule with higher specificity sets the paragraph text color to red, overriding the later blue color.  This is an often-overlooked aspect of CSS that can lead to unexpected behavior.

## Bug Solution
The solution involves understanding and addressing the specificity of CSS selectors. By adjusting the order or using more precise selectors, you can resolve conflicts and achieve the intended styling.  The `bugSolution.css` file provides a corrected version.
