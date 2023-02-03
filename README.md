# Sporty Shoes

#Technologies Used

| Java | 1.8 
| Spring Boot | 2.2.10 
| Swagger-ui | 2.7.0 
| H2 | ---
| JPA | ---
| Spring Security Starter | ---


# Project Structure

This project uses Spring Boot for Model and Controller Implementation
Availaible apis are -
  - /shoe (CRUD)
  - /purchaseReport (CRUD)
  - /shoe/all
  - /purchaseReport/(category|all|dop)

Current Implementation relies simply on String for storing order list.

It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.

Also for admin authentication spring-security-starter has been used with credentials saved in `application.properties` file.

#Docs
For complete docs please use the docs folder in project directory.

