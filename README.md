# Sporty-Shoes
Sporty Shoes - SimpliLearn Phase 3 Assessment
Technologies Used
Java	1.8
Spring Boot	2.2.10
Lombok	---
Swagger-ui	2.7.0
H2	---
JPA	---
Spring Security Starter	---

16 directories, 13 files
Project Structure
This project uses Spring Boot for Model and Controller Implementation Availaible apis are -

/shoe (CRUD)
/purchaseReport (CRUD)
/shoe/all
/purchaseReport/(category|all|dop)
Current Implementation relies simply on String for storing order list.

It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.

Also for admin authentication spring-security-starter has been used with credentials saved in application.properties file.

Docs
For complete docs please use the docs folder in project directory.
