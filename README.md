# JwtAuthentication
Spring security is a filter framework.In the JwtAuthentication application, user can access to url "/welcome" only if it has valid token.The user sends his credentials (username and password) to the server.The server authenticates the credentials and generates a token.The server stores the previously generated token in some storage along with the user identifier and an expiration date.The server sends the generated token to the user.The server, in each request, extracts the token from the incoming request. With the token, the server looks up the user details to perform authentication and authorization:
*If the token is valid, the server accepts the request.
*If the token is invalid, the server refuses the request.


