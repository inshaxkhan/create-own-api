# Blog API Project

A full-stack blog application with a frontend server that consumes a REST API backend. This application allows users to view, create, and edit blog posts through an intuitive web interface.

## Features

- View all blog posts
- Create new blog posts
- Edit existing blog posts
- Real-time API integration with backend server
- Responsive web interface with EJS templating

## Dependencies

- **Express**: Web application framework
- **Body Parser**: Middleware for parsing request bodies
- **Axios**: HTTP client for API requests
- **EJS**: Templating engine for rendering views

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```

## Running the Application

1. Ensure the backend API server is running on `http://localhost:4000`
2. Start the application:
   ```
   node server.js
   ```
3. Open your browser and navigate to `http://localhost:3000`

## API Integration

The application communicates with a backend API at `http://localhost:4000` with the following endpoints:

- `GET /posts` - Retrieve all blog posts
- `GET /posts/:id` - Retrieve a specific post
- `POST /posts` - Create a new post
- `PATCH /posts/:id` - Update an existing post
- `DELETE /posts/:id` - Delete a post

