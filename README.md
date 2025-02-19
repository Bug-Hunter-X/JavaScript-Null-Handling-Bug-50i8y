# JavaScript Null Handling Bug
This repository demonstrates a subtle bug in JavaScript related to null value handling and provides a solution.

## Description
The JavaScript function `foo` adds two numbers together. However, there's an issue with how it handles `null` values. If either `a` or `b` is `null`, it returns without explicitly handling the null case and causing unexpected behavior.

## Bug
The original code is in `bug.js`.  The function should handle the case where one or both input parameters are null.

## Solution
The corrected code is in `bugSolution.js`.  This improved version explicitly checks for null values and provides a suitable default or alternative action, instead of simply returning, which enhances its robustness and avoids unexpected outcomes. 

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript editor or IDE.
3. You can test the code using a simple Node.js environment, or any other JavaScript execution environment.