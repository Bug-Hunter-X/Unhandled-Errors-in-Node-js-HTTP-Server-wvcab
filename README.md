# Unhandled Errors in Node.js HTTP Server

This repository demonstrates a common error in Node.js HTTP servers: the lack of proper error handling.  The original `server.js` file shows a server that doesn't handle potential errors, such as connection failures or request parsing issues.  This can lead to the server crashing or producing unexpected results.

The `serverSolution.js` file provides a solution that gracefully handles errors using `try...catch` blocks and error listeners, ensuring the server remains resilient and stable.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `node server.js`.  Note the lack of error handling.
4. Run `node serverSolution.js`. Observe the improved error handling.

## Learning Outcomes

This example highlights the importance of robust error handling in Node.js applications.  Understanding how to gracefully handle errors is crucial for building reliable and production-ready servers.