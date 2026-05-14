# Product REST API

## About The Project

This project is a simple REST API application developed using Spring Boot.

The API performs CRUD operations for products and returns JSON responses.

---

## Use Cases

### 1. Create Product

A POST request is sent to create a product.

```http
POST /api/v1/products
```

Request body:

```json
{
  "name": "Laptop"
}
```

The product is saved and returned with generated id.

---

### 2. Get Product

The user can get product details using product id.

```http
GET /api/v1/products/1
```

---

### 3. Update Product

Product information can be updated using PUT request.

```http
PUT /api/v1/products/1
```

---

### 4. Delete Product

Product can be removed from database.

```http
DELETE /api/v1/products/1
```

---

## Screenshot

Example of API testing :

<img width="1600" height="846" alt="WhatsApp Image 2026-05-14 at 6 19 54 PM" src="https://github.com/user-attachments/assets/0f207ec3-fafe-4afb-9b59-723672d70bf0" />

---

## Technologies

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Swagger UI

---

## Testing

The API was tested using:

- Swagger UI
- Postman
