# 🚕Taxi-service

The web application will be useful for companies operating in the
transport sector. It allows you to manage drivers and vehicles, link and
scroll through the lists of entities with the possibility of dynamic
changes.

## 📖 Project Structure
 - The project has an N-tier structure and consists of the database layer, the DAO layer for interaction with the database, the service layer which contains the business logic, and the presentation layer.  
 - The DAO layer is built with the JDBC API and have basic CRUD operations.  
 - Servlets are used to receive and respond to client requests.  
 - Filters control access to the store's functionality.  
 - The presentation layer is implemented with JSP.
 - This project also includes custom-made annotations and an injector, which utilizes Reflection API.

## ⚙️ Technologies Used

- Java 11
- Maven 3.1.1
- Maven Checkstyle Plugin
- Javax Servlet API 4.0.1
- JSTL 1.2
- JSP
- Apache Tomcat
- MySQL RDBMS

## ⚡️Running the Project

1. To run the project on your local machine, clone this project into your local folder and open the project in an IDE.
2. Configure Tomcat Server and set up the MySQL DS and MySQL Workbench on your machine.
3. Replicate the database from the project by copying the script from init_db.sql into the MySQL Workbench query editor window.
4. Insert your own MySQL username and login in dbProperties in the ConnectionUtil class.
5. Your MySQL server must be up and running when you launch the project.
6. Done. You did it, enjoy!

