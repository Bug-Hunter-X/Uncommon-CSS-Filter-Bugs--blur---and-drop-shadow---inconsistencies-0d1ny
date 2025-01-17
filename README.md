# Uncommon CSS Filter Bugs

This repository demonstrates some uncommon bugs related to the CSS `filter` property, specifically focusing on the `blur()` and `drop-shadow()` functions.  These issues are more likely to appear in older browsers, particularly Internet Explorer and older versions of Microsoft Edge. 

The `bug.css` file shows the problematic code, while `bugSolution.css` provides potential workarounds or alternative approaches to achieve the desired visual effect.

## Problem Description

- `blur()` inconsistency: In certain browser versions, `filter: blur()` might not apply the blur correctly or cause unexpected rendering issues. 
- `drop-shadow()` rendering issues: A high `drop-shadow()` value can sometimes mask other content or lead to blurry, unreadable text. 

## Solution

- Using feature detection to provide alternative styles for browsers that do not support `blur()` correctly or that have issues with `drop-shadow()`.
- Consider using a JavaScript library to apply blurring effects for better cross-browser compatibility.
- Use a more sophisticated and robust solution to implement drop shadows that are visually pleasing and that do not interfere with the rendering of other elements.