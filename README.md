# Inaccessible Button Element

This repository demonstrates a common accessibility issue in HTML: the improper use of button elements without appropriate ARIA attributes.  The `bug.html` file shows the problematic code.  The solution, provided in `bugSolution.html`, adds the necessary attributes to make the button accessible to users of assistive technology.

## Bug
The original code uses a button without ARIA attributes, making it difficult for screen readers and other assistive technologies to identify and convey its purpose to the user.

## Solution
The solution incorporates ARIA attributes such as `role`, `aria-label`, and `aria-labelledby` to clearly define the button's function and provide meaningful context for assistive technologies.

This is a simple example but highlights the importance of considering accessibility when writing HTML.