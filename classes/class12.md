1. What’s a benefit of using OAuth instead of your own basic authentication?
  - OAuth allows users to register with an existing account, it is a simplified way to authorize someone to use the application.
2. Write the following steps in the correct order:
    1. Ask the client if they want to sign in via a third party
    2. Redirect to a third party authentication endpoint
    3. Receive authorization code
    4. Make a request to the access token endpoint
    5. Receive access token
    6. Make a request to a third-party API endpoint
    7. Register your application to get a client_id and client_secret
3. What can you do with an authorization code?
  - it tells us that the client/user has allowed the server to read data from the user's OAuth account
4. What can you do with an access token?
  - The access token tells the OAuth/Google that our server has the permissions to access their users information that we need.