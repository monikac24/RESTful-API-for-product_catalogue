# Project Overview: RESTful API for Product Catalogue

Client/Organization:
LeadToRev Company

## Objective :
The goal of this project was to develop a robust, efficient, and scalable RESTful API for managing a product catalogue. This API facilitates CRUD (Create, Read, Update, Delete) operations on products, enabling seamless integration with a variety of client applications like e-commerce websites, mobile apps, and internal systems.

The API's purpose is to allow users and administrators to:
a)Add, update, and remove products.
b)Retrieve product details, including availability, ratings, and categories.
c)Search and filter products based on attributes.

## Technologies Used:
The project employed the following technologies:

a) Backend Framework:
1)Spring Boot: To build and manage the RESTful API services.
2)Spring Data MongoDB: To integrate MongoDB as the database.

b)Database:
MongoDB: A NoSQL database to store unstructured and semi-structured data, ideal for flexible product attributes.

c)Language:
Java: The primary language for API development.

d)Tools and Environment:
1)Postman for API testing.
2)IntelliJ IDEA as development environment.
3)Git for version control.


## Key Activities:
1)Requirement Gathering:
Collaborated with  stakeholders to understand business needs.
Identified key product fields like name, description, price, categories, attributes, availability, and ratings.

2)Database Schema Design:
Designed a MongoDB schema to store product data flexibly with nested objects like ratings and availability.

3)API Development:
Designed RESTful endpoints for operations like:
POST /api/products: To add a new product.
GET /api/products: To fetch all products or filter based on attributes.
GET /api/products/{id}: To retrieve a specific product by ID.
PUT /api/products/{id}: To update a product.
DELETE /api/products/{id}: To delete a product.

4)Error Handling:
Implemented structured error responses for invalid inputs (e.g., 400, 404, 500 statuses).

5)Testing:
Conducted functional testing using Postman.

6)Deployment:
Packaged the API with Maven.

## Key Findings:
1)Performance:
MongoDB’s schema-less nature allowed quick development but needed indexing for better search performance.
2)Scalability:
The microservice architecture of Spring Boot made the API modular and scalable for future enhancements.
3)Ease of Use:
Clear API documentation and well-defined responses helped in seamless client integration.

Conclusion
The RESTful API for Product Catalogue successfully met ABC Company's requirements by providing a flexible, fast, and reliable backend solution for product management. The implementation with MongoDB allowed dynamic attributes and easy scalability. K
