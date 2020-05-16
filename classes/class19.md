1. What is the main benefit of a message queue server?
  - it is tasked with routing events messaging between clients. Any connected client can publish a message to the server.
2. Why might we want to initiate messages from an HTTP request?
  - When doing so it "starts" the server and allows it to be able to start putting messages in the queue
3. Is the Message Queue Server a socket.io client, a socket.io server, or an api server?
  - It is all three in combination, you have the api server to run the app, the socket.io server keeps the message queue, to then send it to the clients.