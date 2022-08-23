# Parking-Spot

## Overview
The project for parking spot managment control, is based on the <a href="https://www.youtube.com/watch?v=LXRU-Z36GEU&t=6301s">Spring Boot | Complete Course 2022</a>, by <a href="https://github.com/MichelliBrito">@MichelliBrito</a>. The endpoints presented in this project are simple and resolve CRUD operations, such as create, update, delete and search parking spots. The idea behind the project was mainly to practice the use of Spring Framework, in connection to postGres database, which in my case I switched for MySQL Workbench.

## Tools
JAVA | Spring Boot | Spring Data | OpenAPI 3.0 | Swagger-UI | MySQL Workbench

## How to test the project
1. Download the .zip package of the project and import it into your IDE.
2. Inside the project, under src/main/resources, the application.properties file has to be configured according to the local inviroment:
* spring.datasource.url=jdbc:mysql://localhost:3306/parking_control_db (this line present the default configuration in case you are using MySQL Workbench)
* spring.datasource.username=local-instance-username (in here you can use your MySQL local instance username)
* spring.datasource.password=local-instance-password (in here you can use your MySQL local instance password)
* springdoc.api-docs.path=/api-docs (the path to access the documentation created by using OpenAPI, which will be: http://localhost:8080<strong>/api-docs</strong>)
3. Build the project.
4. Access the endpoints at http://localhost:8080/swagger-ui.html and you should see something like this:

![swagger](https://user-images.githubusercontent.com/80061839/186162130-31d2af30-086e-4e7d-b33b-ff4188c59221.PNG)
