# JSON Web Token (JWT) Testing

## Description
This project is a simple demonstration of using JSON Web Tokens (JWT) for authentication in a Node.js application. JSON Web Tokens are an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. In this project, we implement a basic Node.js application to generate, verify, and decode JWTs for user authentication.

## Features
- **User Authentication:** The project demonstrates how to generate JWTs upon user login and verify them on subsequent requests to authenticate users.
- **Token Expiration:** JWTs are implemented with expiration times to enhance security and prevent token misuse.
- **Token Refresh:** Users can refresh their tokens to extend their session without the need for re-authentication.
- **Middleware Integration:** Middleware functions are used to intercept incoming requests, extract JWTs, and authenticate users before granting access to protected routes.
