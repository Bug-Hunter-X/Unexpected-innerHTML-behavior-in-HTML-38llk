# Uncommon HTML Bug: Unexpected innerHTML Behavior

This repository demonstrates an uncommon bug related to manipulating the `innerHTML` property of an HTML element.  The issue arises when attempting to append new content to the existing `innerHTML` without proper handling of potential existing content.

The `bug.html` file showcases the buggy code. The `bugSolution.html` provides a corrected implementation.

## Bug Description

The bug occurs within the `myFunction` JavaScript function. The original implementation attempts to add a paragraph element to the existing content of the `div` with id "myDiv".  However, this approach leads to unpredictable behavior because it does not handle how existing content is re-rendered.