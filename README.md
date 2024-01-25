This repository contains an implementation of a Blog API using NodeJS, Typescript, and Prisma.

## Features

- CRUD operations for Blog Posts and
- Liking a Blog Post

## Installation

1. Clone the repository
2. Install dependencies by running `npm install`
3. Start the application by running `npm start`

## Endpoints

The following endpoints are available:

- `POST /posts/create`: Create a new Blog Post
- `POST /posts/createPostAndComments`: Create a new Blog Post that allows Comments
- `GET /posts/getall`: Get all Blog Posts
- `GET /posts/get/:id`: Get a Blog Post by ID
- `PUT /posts/update/:id`: Update a Blog Post by ID
- `DELETE /posts/delete/:id`: Delete a Blog Post by ID
- `DELETE /posts/deleteall`: Delete all Blog Posts
- `POST /posts/like`: Like a Blog Post
