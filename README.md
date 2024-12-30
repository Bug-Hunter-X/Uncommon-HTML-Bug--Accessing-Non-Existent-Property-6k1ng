# Uncommon HTML Bug: Accessing Non-Existent Property

This repository demonstrates an uncommon bug in HTML that can occur when working with JavaScript and the DOM. The bug involves attempting to access a property of a DOM element that doesn't exist.

## Bug Description
The `bug.html` file contains a script that tries to access the `nonExistentProperty` of the element with the ID 'myDiv'.  Since this property doesn't exist, a runtime error occurs in the browser's console.

## Solution
The solution is to ensure that you only access properties that actually exist on the DOM element.  You can use a conditional check or other methods (like try...catch) to handle cases where a property might not exist. The corrected code is provided in `bugSolution.html`.