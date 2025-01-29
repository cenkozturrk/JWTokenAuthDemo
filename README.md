# JWT Token Authentication Demo

This project showcases the implementation of **JWT (JSON Web Token)** authentication in a .NET application, providing a secure and stateless way to manage user access and authorization.

## Features

- Demonstrates the generation and validation of JWT tokens.
- Includes user login and token issuance.
- Secures API endpoints using JWT-based authorization.
- Implements role-based access control for added security.

## Prerequisites

Before running this project, ensure you have the following installed:

- [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or later)
- A tool to test API requests (e.g., [Postman](https://www.postman.com/) or cURL)

## How It Works

1. **User Login:**
   - The user sends their credentials (username and password) to the authentication endpoint.
   - A JWT token is generated upon successful login and returned to the user.

2. **Securing Endpoints:**
   - API endpoints are protected with JWT authorization.
   - The token must be included in the `Authorization` header (`Bearer <token>`) of each request.

3. **Token Validation:**
   - The server validates the token's signature, expiration, and claims before granting access to protected resources.

### Visual Guide

1. **Login and Token Generation:**

   ![Login and Token Generation](https://user-images.githubusercontent.com/88964984/187240979-22aea214-0bda-494a-9a80-ec1b2f50d412.png)

2. **Securing API Requests:**

   ![Securing API Requests](https://user-images.githubusercontent.com/88964984/187241081-9f9c26e4-b0a6-4682-aee0-e37d9092e9d1.png)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/jwt-auth-demo.git
   cd JWTokenAuthDemo
