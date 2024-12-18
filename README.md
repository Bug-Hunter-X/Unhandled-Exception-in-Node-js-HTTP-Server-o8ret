# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and provides a solution to handle it gracefully. 

## Bug

The `bug.js` file contains a simple HTTP server that throws an exception if the requested URL is '/error'.  However, this exception is not caught, leading to the server crashing.

## Solution

The `bugSolution.js` file demonstrates how to properly handle the exception using a `try...catch` block. This prevents the server from crashing and allows for more robust error handling.

## How to Run

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` to see the unhandled exception.
4. Run `node bugSolution.js` to see the corrected version.