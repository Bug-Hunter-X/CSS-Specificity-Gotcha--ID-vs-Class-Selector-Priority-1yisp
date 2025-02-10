# CSS Specificity Issue: Unexpected Behavior with ID and Class Selectors

This repository demonstrates an uncommon issue in CSS related to the specificity of selectors. The unexpected behavior stems from the interaction between ID and class selectors within the same rule, where ID selector specificity overrides class selector specificity, even when it seems counter-intuitive based on the element hierarchy.

## The Problem
The bug.css file contains CSS code that showcases the issue.  An element with both an ID and a class exhibits unexpected styling due to the inherent specificity of ID selectors in CSS.

## The Solution
The bugSolution.css file provides a solution by clarifying the selector's precedence and demonstrates how to achieve the desired styling by adjusting the order or specificity of the selectors. 

## How to reproduce the bug
1. Open `bug.html` in your browser.
2. Observe the text color of the element with both ID and class. 

## How the solution works
The solution resolves the issue by correctly handling the CSS selector's specificity and provides the expected result in terms of styling.