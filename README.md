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






# Instagram Backend Design
#### This project is a basic representation of the backend structure for an Instagram-like application. It includes user authentication, user profiles, and post management.

## Technologies Used
- Java
- Spring Boot
- Hibernate (JPA)
- MySQL (or any other database of your choice)
## Models
### User
- Represents a user of the application.
- Contains fields for user information:
  - First Name
  - Last Name
  - Age
  - Email
  - Phone Number
### Post
- Represents a user's post.
- Contains fields for post information:
  - Post ID
  - Created Date
  - Updated Date
  - Post Data 
  -  User 
### AuthenticationToken
- Represents an authentication token for user sessions.
- Contains fields for token information:
  - Token ID
  - Token
  - Token Creation Date
  - User (the associated user)
 ## Controllers
### UserController
This controller handles user-related operations:

- Sign In: Allows users to sign in by providing valid credentials.
- Sign Up: Allows new users to create an account.
- Update User Details: Enables users to update their profile information.
### PostController
This controller handles post-related operations:

- Save Post: Allows users to create and save a new post.
- Get Post: Retrieves post details, including user information.
## API Endpoints
### User Endpoints
- POST /api/user/signin: Sign in with user credentials.
- POST /api/user/signup: Create a new user account.
- PUT /api/user/update: Update user details.
### Post Endpoints
- POST /api/post/save: Create and save a new post.
- GET /api/post/{postId}: Retrieve post details.
## Authentication
- User authentication is required for most endpoints.
- Use the token received during sign-in for all user operations.
## Project Summary
- This Student Application is built using Spring Boot and Java.
- It allows users to perform CRUD operations on student,book,laptop,address and course entities.
- The project follows a structured architecture with controllers, services, and repositories.
- Data is stored in a MySQL database with appropriate relationships.


## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Instagram Backend design :

- **[Vishal Raj]**: Lead developer and project coordinator.
- **[Mainak Ghosh]**: Contributor to the project, helping with [SpringBoot to complete this project].
- **[maven]**: We utilized [maven] for [dependencies] in our project.
- **Stack Overflow Community**: For their invaluable assistance in resolving technical challenges.
- **Spring Framework**: For providing a robust and efficient platform for building our application.


We appreciate the  effort and support that made this project possible.



## Support

For support, email vishalrajbanti@gmail.com.

## thank you.



# Todo APP
#### This project is a basic representation of the backend structure for an Todo application. 
## Technologies Used
- Java
- Spring Boot
- Hibernate (JPA)
- MySQL (or any other database of your choice)
### Todo Model

The Todo Model represents the structure of a todo item. It includes the properties of a todo, such as its title, description, completion status, and creation date.

#### Todo Model Fields

- `id` (integer): Unique identifier for the todo.
- `title` (string): Title of the todo.
- `description` (string): Description of the todo.
- `completed` (boolean): Indicates whether the todo is completed.
- `createdDate` (string): Date and time when the todo was created
## API Endpoints
Here are the available API endpoints:

- GET todos: Get a list of all todos.
- GET todo/{id}: Get a single todo by ID.
- POST todos: Create a new todo.
- PUT todo/{id}: Update an existing todo.
- DELETE todo/{id}: Delete a todo by ID.
## Validation
  The controller enforces validation rules for creating and updating todos. Validation includes checks for required fields, data types, and other constraints. Invalid requests will receive a 400 Bad Request response.
  ## Project Summary
- This Todo App is built using Spring Boot and Java.
- It allows users to perform CRUD operations. 
- The project follows a structured architecture with controllers, services, and repositories.



## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Todo App :

- **[Vishal Raj]**: Lead developer and project coordinator.
- **[Mainak Ghosh]**: Contributor to the project, helping with [SpringBoot to complete this project].
- **[maven]**: We utilized [maven] for [dependencies] in our project.
- **Stack Overflow Community**: For their invaluable assistance in resolving technical challenges.
- **Spring Framework**: For providing a robust and efficient platform for building our application.


We appreciate the  effort and support that made this project possible.



## Support

For support, email vishalrajbanti@gmail.com.

## thank you.

# Food Delivery Platform Application

A comprehensive platform for patients to book appointments with doctors and for administrators to manage healthcare services efficiently.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Models](#models)
  - [Doctor Model](#doctor-model)
  - [Patient Model](#patient-model)
  - [Admin Model](#admin-model)
- [Usage](#usage)
- [Doctor Endpoints](#Doctor-Endpoints)
- [Patient Endpoints](#Patient-Endpoints)
- [Admin Endpoints](#Admin-Endpoints)  
- [Acknowledgments](#Acknowledgments)  
- [Support ](#Support)

## Overview

The Doctors Booking App is designed to simplify the process of booking appointments with healthcare professionals. It offers a user-friendly interface for patients to discover and book appointments. Administrators can manage healthcare services, doctors' schedules, and patient records efficiently.

## Features

- Search for doctors by specialty, location, and availability.
- View detailed doctor profiles, including specialties, qualifications, and patient reviews.
- Patients can schedule, reschedule, or cancel appointments.

- Admin panel for managing doctors, appointments, and patient records.
- Secure handling of patient data and privacy.

## Models
### Doctor Model
The Doctor Model represents the structure of a doctor's profile, including their qualifications, specialties, and appointment availability.

#### Doctor Model Fields
- id (integer): Unique identifier for the doctor.
- name (string): Doctor's full name.
- specialties (array of strings): Medical specialties of the doctor.
- qualifications (string): Educational qualifications and certifications.
- availability (list of objects): Represents the doctor's - appointment schedule.
### Patient Model
The Patient Model represents patient records, including their personal information and appointment history.

#### Patient Model Fields
- id (integer): Unique identifier for the patient.
- name (string): Patient's full name.
- contact (string): Contact details of the patient.
- appointments (list of objects): Represents the patient's appointment history.
### Admin Model
The Admin Model is used to manage the healthcare platform and includes administrative user profiles.

#### Admin Model Fields
- id (integer): Unique identifier for the admin.
- username (string): Admin's username.
- password (string): Encrypted password for admin access.

### Usage
- Patients: Sign up, search for doctors, book appointments, receive reminders, and manage appointments.
- Doctors: Create and manage profiles, set availability, and view patient appointments.
- Admins: Manage doctors, patients, and appointments, ensuring smooth healthcare service operations.

### Doctor Endpoints:

#### Create a Doctor Profile

- Endpoint: POST /api/doctors
- Description: Create a new doctor profile.
- Request: JSON representation of the doctor's profile.

#### Get Doctor Profile
- Endpoint: GET /api/doctors/{id}
- Description: Retrieve a doctor's profile by ID.
Request:
- Path Parameter: id (integer) - ID of the doctor.
#### Update Doctor Profile

- Endpoint: PUT /api/doctors/{id}
- Description: Update an existing doctor's profile by ID.
Request:
- Path Parameter: id (integer) - ID of the doctor.
JSON representation of the updated doctor's profile.

#### Delete Doctor Profile

- Endpoint: DELETE /api/doctors/{id}
- Description: Delete a doctor's profile by ID.
 Request:
  - Path Parameter: id (integer) - ID of the doctor.
  ### Patient Endpoints:

#### Create a Patient Record

- Endpoint: POST /api/patients
- Description: Create a new patient record.
- Request: JSON representation of the patient's record.

#### Get Patient Record
- Endpoint: GET /api/patients/{id}
- Description: Retrieve a patient record by ID.
Request:
- Path Parameter: id (integer) - ID of the patient.
### Update Patient Record

- Endpoint: PUT /api/patients/{id}
- Description: Update an existing patient record by ID.
Request:
- Path Parameter: id (integer) - ID of the patient.
JSON representation of the updated patient record.

#### Delete Patient Record

- Endpoint: DELETE /api/patients/{id}
- Description: Delete a patient record by ID.
Request:
- Path Parameter: id (integer) - ID of the patient.

### Admin Endpoints:
#### Admin Login

- Endpoint: POST /api/admin/login
- Description: Authenticate as an admin and obtain an access token.
Request:
- Username and password in the request body.

#### Manage Doctors

- Endpoint: GET /api/admin/doctors
- Description: Retrieve a list of all doctor profiles.
- Request: None

#### Manage Appointments

- Endpoint: GET /api/admin/appointments
- Description: Retrieve a list of all patient appointments.
- Request: None
## Project Summary
- This Doctor's Booking App is built using Spring Boot and Java.
- It allows users to perform CRUD operations.
- The project follows a structured architecture with controllers, services, and repositories.
- Data is stored in a MySQL database with appropriate relationships.


## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Doctor's Booking APP :

- **[Vishal Raj]**: Lead developer and project coordinator.
- **[Mainak Ghosh]**: Contributor to the project, helping with [SpringBoot to complete this project].
- **[maven]**: We utilized [maven] for [dependencies] in our project.
- **Stack Overflow Community**: For their invaluable assistance in resolving technical challenges.
- **Spring Framework**: For providing a robust and efficient platform for building our application.


We appreciate the  effort and support that made this project possible.



## Support

For support, email vishalrajbanti@gmail.com.

## thank you.

# Food Delivery Platform Application

A comprehensive platform for users to order food from restaurants and for administrators to manage food items and orders efficiently.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Models](#models)
    - [User Model](#user-model)
    - [Food Item Model](#food-item-model)
    - [Order Model](#order-model)
- [Usage](#usage)
    - [User Endpoints](#user-endpoints)
    - [Admin Endpoints](#admin-endpoints)
- [Acknowledgments](#acknowledgments)
- [Support](#support)

## Overview

The Food Delivery Platform Application is designed to simplify the process of ordering food online. It offers a user-friendly interface for users to browse and order food from a variety of restaurants. Administrators can manage food items and orders efficiently, and track the status of deliveries.

## Features

* Browse and order food from a variety of restaurants
* View detailed food item descriptions, including prices, ingredients, and ratings
* Add food items to a cart and place orders
* Track the status of orders
* Administrator panel for managing food items, orders, and user accounts
* Secure handling of user data and privacy

## Getting Started

To get started with the Food Delivery Platform Application, you will need to create an account. Once you have created an account, you can log in and start browsing the menu of restaurants on the platform. To place an order, simply add food items to your cart and proceed to checkout. Administrators can log in to the platform to manage food items, orders, and user accounts.

## Models

### User Model

The User Model represents the structure of a user's profile, including their name, email address, and shipping address.

#### User Model Fields

* id (integer): Unique identifier for the user.
* name (string): User's full name.
* email (string): User's email address.
* shipping_address (string): User's shipping address.

### Food Item Model

The Food Item Model represents the structure of a food item, including its name, description, price, and category.

#### Food Item Model Fields

* id (integer): Unique identifier for the food item.
* name (string): Food item's name.
* description (string): Food item's description.
* price (decimal): Food item's price.
* category (string): Food item's category.

### Order Model

The Order Model represents the structure of an order, including the user who placed the order, the food items ordered, and the total price of the order.

#### Order Model Fields

* id (integer): Unique identifier for the order.
* user_id (integer): ID of the user who placed the order.
* food_item_ids (array of integers): IDs of the food items ordered.
* total_price (decimal): Total price of the order.
* status (string): Status of the order (e.g., "pending", "in progress", "completed").

## Usage

### User Endpoints

* **GET /api/users/{id}**: Retrieve a user's profile by ID.
* **PUT /api/users/{id}**: Update a user's profile by ID.
* **POST /api/orders**: Place an order.
* **GET /api/orders/{id}**: Retrieve an order by ID.
* **GET /api/orders/user/{user_id}**: Retrieve all orders placed by a user.

### Admin Endpoints

* **GET /api/admin/food-items**: Retrieve a list of all food items.
* **POST /api/admin/food-items**: Create a new food item.
* **PUT /api/admin/food-items/{id}**: Update an existing food item by ID.
* **DELETE /api/admin/food-items/{id}**: Delete a food item by ID.
* **GET /api/admin/orders**: Retrieve a list of all orders.
* **PUT /api/admin/orders/{id}**: Update the status of an order by ID.

## Acknowledgments

We would like to express our gratitude to the following individuals and projects for their contributions and support to the Food Delivery Platform Application:

* **[Your Name]**: Lead developer and project coordinator.
* **[List of other contributors]**
* **[List of open source projects used]**

We appreciate the effort and support that made this project possible.

## Support

For support, email [vishalrajbanti@gmail.com].

## Thank you.
<a href="https://github.com/vishalrajbanti">

<div align="center">

  
![][logo-url]
 
</div>
  </a>

[logo-url]: https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp


<div align="center">
  <img src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/welcome.png?raw=true" style="max-width: 100%;" alt="Welcome to my Github Profile" />
  <br />
  <br />
  <img height="50" alt="I am Vishal Raj, and I specialize in backend development." src="images/personalInfo.png" />

</div>

 ### As a proficient backend developer experienced in Spring Boot, I possess a wealth of knowledge in Java and DSA. Currently, I am an apprentice at Geekster platform, where I am consistently enhancing my expertise in the technology field. My fervor for programming has enabled me to gain a comprehensive understanding of various programming languages, and I am perpetually enthusiastic to expand my knowledge further. I am committed, diligent, and constantly endeavoring to enhance my skills to achieve optimal outcomes.


<br>
<br>
<br>

## 🚀💻 Technologies & Tools

  ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
  ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)
  ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code)
  ![IntelliJ](https://img.shields.io/badge/-IntelliJ%20IDEA-black?style=flat-square&logo=jetbrains)
  ![Postman](https://img.shields.io/badge/Postman-black?style=flat-square&logo=postman) 
  ![Apache2](https://img.shields.io/badge/Apache2-black?style=flat-square&logo=apache)
  ![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql)
  ![Java](https://img.shields.io/badge/Java-orange?style=flat-square&logo=java)
  ![Google Chrome](https://img.shields.io/badge/Chrome-black?style=flat-square&logo=google-chrome)
  <div align="center">
<img height="300" alt="My Tech Stacks" src="images/IMGtechstacks.png" />
</div>
<br>
<br>

## ⚡ GitHub Stats
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=vishalrajbanti&theme=gruvbox"/> 
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=vishalrajbanti&theme=gruvbox" alt="Vishal Raj" /><div align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishalrajbanti&theme=gruvbox" />
</div></p>

<br>
<br>
</p>

## 📌Reach me

<p align="center">
   <a href="https://www.linkedin.com/in/vishalrajbanti"><img alt="LinkedIn" title="LinkedIn" height="48" width="48" src="https://github.com/peterthehan/peterthehan/blob/d79cc23b62615a0d38ab46bfa3896a4d4bb30c85/assets/linkedin.svg"></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/vishalrajbanti"><img alt="GitHub" title="GitHub" height="48" width="48" src="https://github.com/peterthehan/peterthehan/blob/d79cc23b62615a0d38ab46bfa3896a4d4bb30c85/assets/github.svg"></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="mailto:vishalrajbanti@gmail.com"><img alt="Vishal Raj | Gmail" title="email" height="48" width="48" 
src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Gmail.svg"></a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   <a href="https://www.hackerrank.com/vishalrajbanti?hr_r=1"><img alt="HackerRank" title="HackerRank" height="48" width="48" 
src="https://upload.wikimedia.org/wikipedia/commons/4/40/HackerRank_Icon-1000px.png"></a>

</p>

<br>


<div align="center">

<img height="120" alt="Thanks for visiting me" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />
<br />

![Visitor Count](https://profile-counter.glitch.me/vishalrajbanti/count.svg)

## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

