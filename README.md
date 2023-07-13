## Hexagonal Application

This is a backend application developed with Spring Boot that implements the hexagonal architecture to adhere to SOLID principles. The goal of the application is to provide an example of the hexagonal architecture through a task CRUD (Create, Read, Update, Delete) functionality. MySQL is used as the database for this application.

- Author
This application was created by @drako9159.

Features
Implementation of the hexagonal architecture.
CRUD operations for tasks.
Integration with MySQL for data storage.
System Requirements
Java 8 or higher.
Maven 3.x.x.
MySQL 5.x.x.
Database Configuration
Before running the application, make sure to configure the MySQL database. You can follow these steps:

Create a database in MySQL named task_db.
Update the database credentials in the application.properties file located in the src/main/resources folder. Make sure to set the correct username and password to access the database.
Running the Application
Follow these steps to run the application:

Clone this repository to your local machine.

Navigate to the project's root folder.

Run the following command to compile and build the project:

````cmd
mvn clean install
````
Once the project build is complete, execute the following command to start the application:
````cmd
mvn spring-boot:run

````
The application will run at http://localhost:8080.

## License
This project is licensed under the MIT License.