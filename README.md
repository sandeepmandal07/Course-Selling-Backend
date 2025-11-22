# Course-Selling-Backend
This project is a backend API for a Course Selling Application, built using Node.js, Express, MongoDB, and JWT authentication. It allows admins to create and manage courses, while users can sign up, sign in, browse courses, and purchase them securely.

This backend project is a complete authentication-based course selling system, built using Node.js, Express, MongoDB, and JWT authentication. It includes separate workflows for Admins and Users, allowing secure login, course creation, and course purchasing.

🚀 Features
🔐 Admin Functionality

-Admin signup & login
-JWT-based authentication
-Ability to create new courses
-Ability to fetch all courses

👤 User Functionality

-User signup & login
-JWT token generation & validation
-Ability to browse courses
-Ability to purchase a course
-Ability to view purchased courses

🧰 Tech Stack

-Node.js – server environment
-Express.js – API framework
-MongoDB + Mongoose – database
-jsonwebtoken (JWT) – authentication
-Postman – API testing

🔑 Authentication Workflow

-Login returns a JWT token
-Token must be passed in the Authorization: Bearer <token> header
-Protected routes validate JWT using middleware

📂 Project Structure
/routes
   ├── admin.js
   ├── user.js
   └── courses.js
/middleware
   ├── admin.js
   └── user.js
/db.js
/config.js
/index.js

📦 What You Learn From This Project
-How to build secure REST APIs
-How JWT works
-How to protect routes with middleware
-MongoDB schema modeling
-Real-world backend structure
