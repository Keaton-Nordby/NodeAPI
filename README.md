# CRUD App with JWT Authentication

A **basic CRUD application** built with Node.js and Express, featuring **JWT authentication**, **user registration/login**, and secure handling of data. This app demonstrates best practices with modern tools including **bcryptjs**, **cookie-parser**, **helmet**, **joi**, **jsonwebtoken**, **mongoose**, and **nodemailer**.  

---

## Features

- **User Authentication**
  - Register new users with hashed passwords (`bcryptjs`)
  - Login with JWT token authentication
  - Secure HTTP-only cookies for sessions (`cookie-parser`)
- **CRUD Operations**
  - Create, Read, Update, Delete data securely
- **Validation**
  - Input validation using `joi`
- **Security**
  - Helmet middleware for securing HTTP headers
- **Database**
  - MongoDB integration using `mongoose`
- **Email Notifications**
  - Send emails via `nodemailer` (e.g., for password resets or confirmations)
- **JWT Authorization**
  - Protect routes using JSON Web Tokens (`jsonwebtoken`)

---

## Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB (via Mongoose)
- **Authentication:** JWT (JSON Web Tokens)
- **Security:** bcryptjs, helmet, cookie-parser
- **Validation:** joi
- **Email:** nodemailer

---
