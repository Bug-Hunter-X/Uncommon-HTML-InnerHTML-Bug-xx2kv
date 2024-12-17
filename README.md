# Uncommon HTML Bug: Unexpected InnerHTML Behavior

This repository demonstrates an uncommon bug related to the `innerHTML` property in HTML.  Improper usage of `innerHTML` when adding multiple elements can lead to unexpected behavior and loss of event handlers. 

The `bug.html` file shows the problematic code, while `bugSolution.html` provides a corrected and more robust approach.

## Bug Description
When using `innerHTML` to add multiple elements, it's important to correctly construct the HTML string.  Simply concatenating element strings together might lead to only the last element taking effect or unexpected element hierarchy.  Event handlers may be lost during the process.