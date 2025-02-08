# Uncommon HTML Error: DOM access and undefined variable

This repository demonstrates two common errors in HTML:

1. **Accessing a DOM element before it is loaded:** Attempting to access an element using `document.getElementById` before the element is fully parsed in the DOM will result in a `null` value and hence an error.
2. **Using an undefined variable:** Referencing a variable that has not been declared or assigned a value can lead to unexpected behavior or errors.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file provides a corrected version.  Learn how to avoid these common pitfalls!