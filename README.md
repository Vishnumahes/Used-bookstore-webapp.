# Used Textbook Buy/Selling Spring Boot Project

## Introduction
This project was made as part of CSE687-Object Oriented Design. It is a Used Textbook Buy/Selling platform developed with Spring Boot, emphasizing Object Oriented Design principles. It features a modular, maintainable, and scalable architecture, ideal for buying and selling used books.

## Features
- Buying and selling used books
- Comprehensive list and detailed view of books
- User management functionalities
- Modularization
  - Modules: Controller, Exception, Model, Repository, Service


## Endpoints

### Book Service Endpoints
- `GET /books`: Retrieve all books.
- `GET /books/id/{bookId}`: Fetch book by ID.
- `POST /AddBook`: Add a new book.
- `PUT /UpdateBook`: Update book details.
- `DELETE /DeleteBook/{bookId}`: Delete a book.

### User Service Endpoints
- `GET /users/allUsers`: Get all users.
- `GET /users/{userId}`: Fetch user by ID.
- `POST /users/create`: Create a new user.
- `PUT /users/update`: Update user details.
- `DELETE /users/delete/{userId}`: Delete a user.

### Book Copy Service Endpoints
- `GET /bookcopies`: Get all book copies.
- `GET /bookcopies/{copyId}`: Fetch book copy by ID.
- `POST /bookcopies`: Create a new book copy.
- `PUT /bookcopies/update`: Update book copy details.
- `DELETE /bookcopies/delete/{copyId}`: Delete a book copy.

### Transaction Service Endpoints
- `POST /transactions/buy`: Buy a book.
- `POST /transactions/sell`: Sell a book.

## Database Design
![Database Design]((https://github.com/Vishnumahes/Used-bookstore-webapp./assets/45967733/fba96045-5cb6-4930-8373-92052a8f47f2))

## Object Oriented Design
Principles like Encapsulation, Inheritance, and Composition are implemented.

## Design Patterns
- **Template Design Pattern**
- **Singleton Design Pattern** used in Service and Controller classes.

## Deployment
Easily deployable via Docker Compose. Just use the following command:
```sh
docker-compose up
