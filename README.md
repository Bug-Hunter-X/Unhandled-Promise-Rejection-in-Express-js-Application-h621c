# Unhandled Promise Rejection in Express.js Application

This repository demonstrates a common error in Express.js applications: failure to properly handle errors that may arise from asynchronous operations.  In the `bug.js` file, you'll find an Express.js server that includes an asynchronous function that can throw an error. The error handling is incomplete, leading to unhandled promise rejections and potential application instability.  The solution, in `bugSolution.js`, shows how to effectively catch and handle these errors gracefully.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install Express.js
3. Run `node bug.js`
4. Observe the console output (or lack thereof) when the server throws an error. 
5. Run `node bugSolution.js` to see the improved error handling.

## Solution
The improved code implements comprehensive error handling within the asynchronous operation. The solution effectively handles and logs these errors, preventing unhandled promise rejections and maintaining application stability.