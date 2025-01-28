# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  missing error handling for invalid input.  Specifically, the example shows a route that retrieves a user by ID, but fails to handle cases where the ID is not a valid integer.

The `bug.js` file contains the buggy code, which attempts to parse the user ID as an integer without any error handling. This can lead to unexpected behavior or crashes if the ID is not a number.

The `bugSolution.js` file provides a corrected version with robust error handling, preventing crashes and providing informative error responses.