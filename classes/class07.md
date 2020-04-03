# Questions
  1. What code does the server actually run?
    * any code that is meant to be run indefinitely will run on a server
  2. What Express/HTTP operations map to CRUD operations?
    * They are GET, POST, PUT and DELETE, Express allows us to make the end points for them ourselves
  3. What does res.send() do?
    * it is used to send data back to the client in the properly formatted way
  4. What is the order of operations for the three categories of middleware (handler, application, route)?
    * Application: runs whenever the server receives a request
    * Route: Runs whenever the server receives a request to a specific url endpoint
    * Handler: Runs when the server receives a specific method request to specific route
  5. What is the parameter next used for?
    * It allows us to call the "next" middleware in the chain