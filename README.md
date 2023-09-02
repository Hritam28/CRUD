# Spring Boot + Angular 15 CRUD Example

This is a full-stack CRUD (Create, Read, Update, Delete) application built with Angular 15 for the front-end and Spring Boot for the back-end. It manages tutorials, each with id, title, description, and published status. You can perform operations like creating, retrieving, updating, and deleting tutorials. There's also a search functionality for finding tutorials by title.

![spring-boot-angular-15-example-crud.png](spring-boot-angular-15-example-crud.png)

## Getting Started

To run both the back-end and front-end in one place, follow the steps provided in the tutorial:

[Integrate Angular with Spring Boot Rest API](https://www.bezkoder.com/integrate-angular-spring-boot/)


## Running the Spring Boot Application

Use the following command to run the Spring Boot server:

```bash
mvn spring-boot:run

The Spring Boot server will expose its API on port 8081.

Running the Angular Client
To run the Angular client, follow these steps:

Install the required dependencies:
bash
npm install
Start the Angular development server on port 8081:
bash
ng serve --port 8081
