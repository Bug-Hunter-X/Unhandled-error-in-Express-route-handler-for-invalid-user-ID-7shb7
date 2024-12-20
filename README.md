# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version.

The error occurs when the route `/users/:id` receives an invalid ID (e.g., not a number).  The original code attempts to parse this into an integer without any validation, leading to potential crashes or unexpected behavior.  The solution adds input validation and more robust error handling to prevent these issues.