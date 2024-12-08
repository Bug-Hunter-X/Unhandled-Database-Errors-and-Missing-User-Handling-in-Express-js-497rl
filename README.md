# Unhandled Errors in Express.js
This repository demonstrates a common error in Express.js applications: inadequate error handling for database operations and scenarios where requested resources are not found.

The `bug.js` file showcases an Express.js route that fetches user data from a database.  It lacks proper error handling, leading to application crashes or unexpected behavior if the database query fails or the requested user does not exist.

The `bugSolution.js` file provides a corrected version with robust error handling using appropriate HTTP status codes and informative error messages.  This improved version gracefully handles database errors and the absence of the requested user.