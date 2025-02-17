# Spring-Boot-Web-Application

This project was developed during a college hackathon to demonstrate the implementation of a Spring Boot Web Application using JSP/Thymeleaf, JPA, Hibernate 5, and MySQL. It also includes form validation with the Java Bean Validation API.  

## 🏆 Hackathon Project Overview  
During the hackathon, our team built a web application focusing on:  
- Spring MVC for handling HTTP requests and responses.  
- JPA & Hibernate 5 for efficient database management.  
- Thymeleaf & JSP as front-end templating engines.  
- Multiple Database Integration to handle different data sources.  
- Form Validation with Java Bean Validation API to ensure user input meets required constraints.  

## 🛠️ Technologies Used  
- Spring Boot 2 – Simplifies configuration and setup.  
- Spring MVC – Web framework for handling requests.  
- JSP / Thymeleaf – Templating engines for rendering views.  
- JPA & Hibernate 5 – ORM for database interaction.  
- MySQL – Relational database for data storage.  
- Spring Boot Validation – Implements form validation with Java Bean Validation API.  

## 🚀 Features  
✅ Spring MVC Implementation – Handles HTTP requests and responses.  
✅ Multiple Data Source Configuration – Uses multiple MySQL databases in a single application.  
✅ Form Validation – Ensures user input follows specific constraints.  
✅ Java Bean Validation API – Uses annotations for automatic validation.  

## 🔍 Form Validation Constraints  
The project uses Java Bean Validation API to enforce validation rules:  

- `@NotEmpty` – Field must not be null or empty.  
- `@NotBlank` – Field must not be null and must contain at least one non-whitespace character.  
- `@NotNull` – Field must not be null.  
- `@Email` – Ensures a well-formed email address.  
- `@Min(value)` – Field must be a number greater than or equal to the given minimum.  
- `@Max(value)` – Field must be a number less than or equal to the given maximum.  
- `@Size(min, max)` – Field size must be within the specified range (applies to strings, collections, and arrays).  

