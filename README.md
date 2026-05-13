# Product REST API Application

## About Project

This project is a simple REST API created using Spring Boot.

The application performs basic CRUD operations for products and demonstrates how REST endpoints work in Spring framework.

---

## Main Features

The API allows users to:

- Create products
- View product details
- View all products
- Update product information
- Delete products

The project also includes exception handling and Swagger API testing.

---

## Technologies

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Swagger UI
- Maven

---

## Project Structure

Project contains:

- Controller layer
- Service layer
- Repository layer
- Domain classes
- Exception handling classes

---

## Running the Application

1. Open the project in IntelliJ IDEA
2. Reload Maven project
3. Run the application

Server starts on:

```text
http://localhost:8080
```

---

## Swagger Documentation

Swagger UI:

```text
http://localhost:8080/swagger-ui/index.html
```

---

## H2 Database Console

```text
http://localhost:8080/console
```

---

## API Examples

### Create Product

```http
POST /api/v1/products
```

### Get Product

```http
GET /api/v1/products/1
```

### Get All Products

```http
GET /api/v1/products
```

### Update Product

```http
PUT /api/v1/products/1
```

### Delete Product

```http
DELETE /api/v1/products/1
```

---

## API Testing

The endpoints were tested using:

- Swagger UI
- Postman
