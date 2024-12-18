# Simple API with TypeScript, Node.js, Express, and Prisma

This project is a simple API built using **TypeScript**, **Node.js**, **Express**, and **Prisma**, adhering to **Clean Architecture** and **SOLID principles**. The API uses **SQLite** as its database and currently supports the following operations:

- **GET /products**: Fetch all products.
- **POST /products**: Add a new product.

## Features

- Written in TypeScript for type safety.
- Organized using Clean Architecture for separation of concerns.
- SOLID principles to ensure maintainability and scalability.
- Prisma ORM for database management with SQLite.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Project Structure

The project follows Clean Architecture principles:

```
src/
├── usecases/    # Business logic (use cases)
├── domain/         # Domain models and interfaces
├── infra/          # Frameworks and tools (e.g., Prisma, Express setup)
└── main.ts         # Application entry point
```

