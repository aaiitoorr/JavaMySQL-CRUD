# MySQL CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application built with **Spring Boot** and **MySQL**.
It provides basic operations to manage user data such a first name, last name and email.
It uses RESTful APIs

## Features
   - **Create**: Add a new user to the database
   - **Read**: Fetch all users or get a specific user by their ID
   - **Update**: Update an existing user's information
   - **Delete**: Delete an existing user by their ID

## Technologies
   - Java
   - Spring boot
   - MySQL
   - Docker
   - JPA
   - Rest API (Get, Post, Put, Delete)
   - Maven for build management

## Prerequisites

Before running the project, ensure you have the following installed:
   - Java 17 or higher
   - MySQL server running on port 3306 
   - Maven

## Setup 

   1. **Clone the repository**
   ```bash
   git clone https://github.com/aaiitoorr/MySQL-Crud.git
   cd MySQL-Crud
   ```
   2. **Create MySQL database**
      - Create a database called `user` in MySQL server (Or modify the `application.properties` and choose the database)
      - Ensure that MySQL is running on `localhost:3306`
   3. **Configure the `application.propierties` with your properties or with the following ones by default.**
   ```Propierties
   spring.application.name=crud
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   server.port=4000
   spring.datasource.url=jdbc:mysql://localhost:3306/user
   spring.datasource.username=root
   spring.datasource.password=Admin1234
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
   debug=true
   ```
