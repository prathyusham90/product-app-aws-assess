# product-app-aws-assess
This app is built for assessment for Prathyusha

# Spring Boot Product Application

Simple CRUD product application built with Spring Boot.

## Endpoints

- `GET /api/products` - list all products
- `GET /api/products/{id}` - get product by id
- `POST /api/products` - create a new product
- `PUT /api/products/{id}` - update a product
- `DELETE /api/products/{id}` - delete a product

## Run

```bash
mvn spring-boot:run
```

## Sample JSON

```json
{
  "name": "Keyboard",
  "description": "Mechanical keyboard",
  "price": 79.99
}
```
