# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  The bug arises from attempting to modify a nested element after completely replacing the parent element's `innerHTML`.  This can lead to unexpected behavior and runtime errors. The solution showcases best practices for efficiently managing DOM elements. 

## Bug Description
The bug is caused by the inefficient usage of `innerHTML` to replace entire content and after that it is trying to access nested element, which is now detached from the DOM, which leads to runtime error.