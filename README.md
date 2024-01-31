# Custermer Management Application

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#Technologies-Used)
- [Data Models](#Data-Models)

- [API Endpoints](#API-Endpoints)
- [Project Summary](#Project-Summary)
  
- [Acknowledgments](#Acknowledgments)  
- [Support ](#Support)



### Overview
This Customer Management Application  is designed to handle various types of relationships  among data models and provide CRUD (Create, Read, Update, Delete) operations for each model. 

### Technologies Used
- Framework: Spring Boot
- Language: Java
- Database: MySQL 
- Dependency Management: Maven
- Security : JWT(jason web token)
### Data Models

### Customer
- Represents a Customer .
- Contains fields for Customer information information:
  - Id
  - first_name
  - last_name
  - street
  - address
  - city
  - state
  - email
  - phone 

 
### AuthenticationToken
- Represents an authentication token for user sessions.
- Contains fields for token information:
  - JWT Token 
 
### Project Structure
The project structure is organized as follows:

- Main : Contains the Java source code.
- controller: Contains controller classes for handling HTTP requests.
- model: Contains entity classes for the data models.
- repository: Contains repository interfaces for database operations.
- service: Contains service classes for business logic.
- security: contains security related details.
- resources: Contains application configuration files, including application.properties or application.yml.
- test: Contains test classes.
- Setup
    Clone the repository to your local machine:

 - bash
- Copy code
- git clone 
  - https://github.com/vishalrajbanti/CustomerManagement.git
- Open the project in your chosen IDE.

- Configure your database connection in the application.properties or application.yml file.

- Run the Spring Boot application.

 

## API Endpoints

- POST   /customer : Creates a new customer.
- PUT    /update/customer: Updates an existing customer. 
- DELETE user/signOut : sign out a sign in user.
- GET   /customer/id/{id} :  Retrieves a single customer based on the provided ID.
- GET     /customer : Retrieves a list of all customers.
- DELETE  /customer/id/{id} : Deletes a customer based on the provided ID.


## Authentication
- Customer authentication is required for most endpoints.
- Jwt token is used  for all customer operations.



## Project Summary
- This Customer MAnagement Application is built using Spring Boot and Java.
- It allows users to perform CRUD operations on Customer entities.
- The project follows a structured architecture with controllers,models, services ,security and repositories.
- Data is stored in a MySQL database with appropriate relationships.


## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Customer management Application :

- **[Vishal Raj]**: Lead developer and project coordinator.
- **[maven]**: We utilized [maven] for [dependencies] in our project.
- **Stack Overflow Community**: For their invaluable assistance in resolving technical challenges.
- **SpringBoot Framework**: For providing a robust and efficient platform for building our application.
- **AWS**: for proving a public server to deploy the Application.

We appreciate the  effort and support that made this project possible.



## Support

For support, email vishalrajbanti@gmail.com.

## thank you.






