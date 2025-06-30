# Pets API

A simple RESTful API for managing pets, built with **Express.js**. The project includes Swagger documentation and supports basic CRUD operations for pets.

## Features

- **Express.js** server
- **CORS** enabled
- **Swagger UI** for API documentation (`/api-docs`)
- CRUD endpoints for pets (`/pets`)
- Modular route and controller structure
- Ready for testing with Jest and Supertest

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:
    ```sh
    git clone <your-repo-url>
    cd pets
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

### Running the Server

Start the server:
```sh
npm start
```
The server will run at [http://localhost:3000](http://localhost:3000).

### API Documentation

Visit [http://localhost:3000/api-docs](http://localhost:3000/api-docs) for interactive Swagger API docs.

### Running Tests

```sh
npm test
```

## Project Structure

```
pets/
├── app.js
├── routes/
│   └── pets.routes.js
├── controllers/
│   └── pets.controllers.js
├── models/
│   └── pets.models.js
├── db/
│   └── db.js
├── package.json
└── ...
```

## Endpoints

- `GET /pets` — List all pets
- `GET /pets/:id` — Get a pet by ID
- `POST /pets` — Add a new pet
- `PUT /pets/:id` — Edit a pet
- `DELETE /pets/:id` — Delete a pet

## License

ISC

---
