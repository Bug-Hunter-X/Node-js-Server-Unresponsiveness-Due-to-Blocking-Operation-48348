# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js: server unresponsiveness caused by a blocking operation in the request handler. The `server.js` file contains a server that performs a long-running operation (simulated here with a `while` loop) which blocks the event loop and the application becomes unresponsive.

The solution is demonstrated in `server-solution.js`, illustrating how to use asynchronous programming techniques to avoid blocking the event loop and handle multiple requests efficiently.