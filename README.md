# Unresponsive Node.js Server

This repository demonstrates a common issue in Node.js where a long-running synchronous operation in the request handler causes the server to become unresponsive.  The `server.js` file contains the buggy code, while `serverSolution.js` shows how to fix it using asynchronous operations.