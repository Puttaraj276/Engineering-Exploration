Spring Boot E-Commerce Project

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [Screen Shot](#screenshot)

# Software And Tools Required

## 1. Java JDK 8+

Ensure that you have Java JDK 8 or a later version installed. You can download the latest version of Java JDK from the official website: [Java Downloads](https://www.oracle.com/java/technologies/javase-downloads.html)

## 2. Spring Tool Suite or Eclipse EE (Enterprise Edition)

Choose an Integrated Development Environment (IDE) for Java development. You can use either Spring Tool Suite (STS) or Eclipse EE (Enterprise Edition). Download and install your preferred IDE:

- [Spring Tool Suite](https://spring.io/tools) - An IDE based on Eclipse, tailored for developing Spring applications.
- [Eclipse EE](https://www.eclipse.org/downloads/packages/release) - The Eclipse IDE for Java EE Developers.

## 3. MySQL Server

Install MySQL Server, which is used as the database for your Spring Boot E-Commerce Project. Download the MySQL Server from the official website: [MySQL Downloads](https://dev.mysql.com/downloads/mysql/)

## 4. MySQL Workbench

MySQL Workbench is a visual database design tool and administration tool for MySQL. Install MySQL Workbench to interact with and manage your MySQL database. Download it from the official website: [MySQL Workbench Downloads](https://dev.mysql.com/downloads/workbench/)


## Installation

1. Clone the repository to your local machine.

2. Ensure you have Java and Maven installed.

3. Configure the database properties in \`application.properties\`.

4. Run the application using the following command:
   \```bash
   mvn spring-boot:run
   \```
5. Generate App password from Google.
6. Generate API keys from the Razorpay website.

## Usage

### Customer

1. Create an account or log in.
2. Browse through available products.
3. Add desired items to the cart.
4. Proceed to checkout and complete the payment process.
5. Add products to the wishlist and manage the wishlist.
6. Make use of integrated payment with Razorpay for secure transactions.

### Merchant

1. Create a Merchant account or log in.
2. Add new products to the platform.
3. Update product information.
4. Delete products that are no longer available.

### Admin

1. Log in with Admin credentials.
2. Approve new products added by Merchants.
3. View a comprehensive list of all Merchants and Customers.

## Features

- **User Authentication:** Secure user authentication and authorization using Spring Security and JWT tokens.
- **Product Management:** Easy product search and detailed product pages.
- **Cart Functionality:** Manage your shopping cart with add, remove, and update capabilities.
- **Payment Integration:** Seamless integration with Razorpay payment gateways.

  - **JWT Token Validation:** Utilize JWT tokens for secure user validation.
  - **Testing with Postman:** Easily test the functionalities using Postman for API testing.
     
  - **Swagger Documentation:** Explore and understand the APIs through interactive Swagger documentation.
    
  - ** Swagger link eg: "http://localhost:8080/swagger-ui/index.html#/"

## Contributing

We welcome contributions! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.
4. For major changes, please open an issue first to discuss potential improvements.
## Screen Shot

https://github.com/vikashalikatti/Boot-restapi-shopping/tree/master/Postman%20Pic
