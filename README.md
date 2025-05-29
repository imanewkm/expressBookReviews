# IBM Backend BookReview Final Project

## Overview
This is the final project for the IBM Backend Development course, featuring a comprehensive book review application built with Express.js and Node.js.

## Features
- User authentication and authorization
- Book catalog management
- Review and rating system
- RESTful API endpoints
- JWT token-based security

## Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager
- MongoDB or similar database

## Installation
1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd expressBookReviews\final_project
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the application:
    ```bash
    npm start
    ```

## API Endpoints
- `GET /books` - Retrieve all books
- `GET /books/:id` - Get book by ID
- `POST /books` - Add new book (authenticated)
- `PUT /books/:id` - Update book (authenticated)
- `DELETE /books/:id` - Delete book (authenticated)
- `POST /auth/register` - User registration
- `POST /auth/login` - User login
- `POST /books/:id/reviews` - Add review (authenticated)

## Project Structure
```
expressBookReviews/
├── routes/
├── models/
├── middleware/
├── controllers/
├── config/
├── package.json
└── README.md
```

## Technologies Used
- Express.js
- Node.js
- MongoDB/Mongoose
- JWT (JSON Web Tokens)
- bcrypt for password hashing

## License
This project is part of the IBM Backend Development course.