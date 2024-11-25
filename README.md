# Online Food Delivery  System
<p>
        <h1>TEAM</h1>
        <ol>
        <li>
        PUSHPANDER KUMAR : 2023mt93337@wilp.bits-pilani.ac.in     
        </li>
          <li>
        RITIK MAHESHWARI : 2023mt93296@wilp.bits-pilani.ac.in   
        </li>
         <li>
        RICHA KHARE : 2023mt93101@wilp.bits-pilani.ac.in    
        </li>
        <li>
        RAJVARDHANI RAJENDARRAO KADU: 2023mt93458@wilp.bits-pilani.ac.in    
        </li>
        </ol>
</p>
    <br>

This project is developed by a team of 4 members with the help of the Spring-Boot framework. The main objective of this Web services application is to cater needs of front-end developers to call different types of API as per the requirement.


## Tech Stack and Tools
- Java
- Spring Boot Framework
- Spring Data JPA
- Hibernate
- MySQL
- Swagger-UI
- Lombok

## ER- Diagram
<p>
        <img
        align="center"
        src="https://github.com/parimalbiswas/tropical-jellyfish-2222/blob/main/ER%20-DIA.jpg?raw=true"
        alt="Coding"
        width="700"
        style="display: block"/>
    </p>
    <br>


## Modules
- Login Module
- Restaurant Module
- Customer Module
- Order Module
- Items Module
- Food Cart Module
- Bill Module

## Features
- Customer and Admin authentication & validation with session uniqueId.
- Admin Features:
 - Only registered admins with valid session id can do the CRUD operations like add/update/delete.
 - Admin can add restaurants and food items.
 - Admin can remove restaurants and items.
 
- Customer Features:
 - Customer can register themselves with the application.
 - Customer can login to get the valid session token(id).
 - View list of available items.
 - Add items to food cart, view cart details, placing the order, update and access other features.
  
## Installation & Run
- To run this API server, you should update the database configuration inside the application.properties file which is present in the src/main/resources folder.
- Update the port number, username and password as per your local database configuration.
server.port=8008
spring.datasource.url=jdbc:mysql://localhost:3306/FoodExpress;
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=your_username_here
spring.datasource.password=your_password_here
```
## API Root Endpoint
```
https://localhost:8888/
```
```
https://localhost:8888/swagger-ui.html
```
