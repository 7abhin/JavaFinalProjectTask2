# First REST API - Spring Boot

Simple REST API project created using Spring Boot.

## Technologies

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Swagger UI

---

## Features

- Create product
- Get product by id
- Get all products
- Update product
- Delete product
- Exception handling
- Swagger documentation

---

## Run Project

1. Open project in IntelliJ
2. Reload Maven
3. Run `FirstRestApiSpringApplication`

Application runs on:

```text
http://localhost:8080
````

---

## Swagger UI

```text
http://localhost:8080/swagger-ui/index.html
```

---

## H2 Console

```text
http://localhost:8080/console
```




## API Endpoints

### Create Product

```http
POST /api/v1/products
```
---

### Get Product

```http
GET /api/v1/products/1
```

---

### Get All Products

```http
GET /api/v1/products
```

---

### Update Product

```http
PUT /api/v1/products/1
```


---

### Delete Product

```http
DELETE /api/v1/products/1
```

---

