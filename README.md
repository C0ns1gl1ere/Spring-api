# Product API Project

This is a REST API application for product management built with Java Spring Boot.

## 🛠 Technologies
* **Java 21**
* **Spring Boot 3.4.1**
* **H2 Database** (in-memory database)
* **Swagger UI** (for documentation and testing)

## 📸 Screenshots

### 1. Main Documentation Page (Swagger)
Shows all available API methods:

![Swagger Main Page](images/swagger-main-page.png.png)

### 2. Successful Product Creation
Example of a POST request returning **201 Created**:

![Product Created Success](images/product-created-success.png)

## 🚀 How to Run
1.  Open the project in **IntelliJ IDEA**.
2.  Run the `FirstRestApiSpringApplication` class.
3.  The server will start on port `8080`.
4.  Open your browser: [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)

## 🔌 API Endpoints
* `GET /api/v1/products` — Get list of all products
* `GET /api/v1/products/{id}` — Find product by ID
* `POST /api/v1/products` — Create a new product
* `PUT /api/v1/products/{id}` — Update an existing product
* `DELETE /api/v1/products/{id}` — Delete a product

### JSON Example for POST:
```json
{
  "name": "iPhone 16 Pro Max"
}