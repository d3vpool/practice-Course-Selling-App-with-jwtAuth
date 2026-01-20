# Course Selling App (JWT Auth)

Backend service for a course selling platform built using Node.js, Express, MongoDB, and JWT authentication.  
The project focuses on implementing secure authentication, role-based access, and protected routes with persistent data storage.

## Tech Stack
- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT)

## Features
- Separate authentication flows for Admins and Users
- JWT-based signin and authorization
- Protected routes using middleware
- Admins can create and view courses
- Users can view, purchase, and list purchased courses
- All data stored persistently in MongoDB

## Authentication
After signin, a JWT is issued.  
For all protected routes, the token must be sent in the request headers:
```text
Authorization: Bearer <your-token>
```


## Purpose
This project was built as part of a learning exercise to understand backend architecture, JWT authentication, middleware design, and MongoDB-based data handling in a real-world backend application.
