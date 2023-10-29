# Food Delivery Platform API

This is the README file for the Food Delivery Platform API project, which provides a set of RESTful endpoints for managing food items, user authentication, and order management. This document will provide an overview of the project structure, API endpoints, and important information for developers and users.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
- [Authentication](#authentication)
- [Contributing](#contributing)
- [License](#license)

## Project Overvieww

The Food Delivery Platform API is a backend service for a food delivery application. It allows users to perform various operations, including adding, updating, and removing food items, creating orders, and managing user accounts. This API is designed to be integrated with a frontend application to provide a complete food delivery experience.

## Technologies Used

The project is built using the following technologies and libraries:

- Java
- Spring Boot
- Spring Data JPA
- Spring Validation
- MySQL
- Lombok
- Springdoc OpenAPI for API documentation
- JavaMail for email functionality

## Project Structure

The project is structured as follows:

- `com.geekster.Food_Delivery_Platform_API.controller`: Contains controller classes that define REST endpoints for various operations.
- `com.geekster.Food_Delivery_Platform_API.dto`: Contains DTO (Data Transfer Object) classes for input and output data.
- `com.geekster.Food_Delivery_Platform_API.model`: Contains entity classes that represent the data structure of the application.
- `com.geekster.Food_Delivery_Platform_API.service`: Contains service classes for business logic.
- `pom.xml`: Maven project configuration file.

## API Endpoints

### AdminController

- `POST /food`: Add a new food item.
- `GET /foods`: Get a list of all food items.
- `PUT /update/{foodId}`: Update a food item by ID.
- `DELETE /delete/{foodId}`: Delete a food item by ID.
- `GET /getAllOrders`: Get a list of all orders.

### UserController

- `POST /user/signUp`: Register a new user.
- `POST /user/signIn`: Sign in with a user account.
- `POST /CreateOrder`: Create a new order.
- `GET /getOrder/{orderId}`: Get an order by ID.
- `DELETE /order/cancel`: Cancel an order.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.

2. Set up a MySQL database and update the database configuration in the `application.properties` file.

3. Build the project using Maven: `mvn clean install`.

4. Run the application: `mvn spring-boot:run`.

5. Access the API endpoints using a tool like Postman or integrate them into your frontend application.

## Authentication

The API uses token-based authentication for certain endpoints. To access these endpoints, you must provide a valid email and token. You can use the `POST /user/signIn` endpoint to obtain a token when signing in. This token should be included in the request headers when accessing authenticated endpoints.


## **[👨‍💻 Rahul Shukla](#heading-ids)** ##
____

- Twitter: [@Rahul.twitter](https://twitter.com/elite_rahul)

- Github: [@Rahul-Github](https://github.com/elite_rahul)


🤝 **Contributing**
___
Contributions, Thanks to everyone , contributing with me and know about more myself [visit my profile](https://www.instagram.com/45_elite/).

**Show Your Support**
___
Give a ⭐if this project helped you!

- ```bash
  BECOME A SOFTWARE DEVELOPER 👩‍💻

<!-- Here something icon -->

📝 **License**
___
Copyright © 2023 [Rahul Shukla](#heading-ids).

This project is [Food Delivery API](https://choosealicense.com/licenses/mit/) licensed.

___
*This README was generated with* 🧡 *by [readme-md-generator](https://www.makeareadme.com/)*
