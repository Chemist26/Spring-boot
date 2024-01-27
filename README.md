# HPlus Application

## Overview

HPlus Application is a demo project built with Spring Boot. It showcases the integration of Spring Boot with Spring MVC, Spring Data JPA, and MySQL for a web application.

## Prerequisites

Before running the application, ensure that you have the following software installed:

- [Java Development Kit (JDK)](https://adoptopenjdk.net/) - Version 17
- [MySQL Server](https://dev.mysql.com/downloads/mysql/) - Version 8.0.23
- [Apache Maven](https://maven.apache.org/) - Version 3.8.3

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hplusapp.git
   
2. Navigate to the project directory:
   ```bash
   cd hplusapp
3. Update src/main/resources/application.properties with your MySQL database configuration.
   ```bash
   mvn clean install
   java -jar target/hplusapp-0.0.1-SNAPSHOT.war

  The application will be accesible at http://localhost:8080.
  
4. Build and run the application:

## Project Structure
- `src/main/java/com/test/hplus` - Java source code
- `src/main/resources` - Configuration files
- `src/main/webapp/WEB-INF/jsp` - JSP files
- `src/main/webapp/static/css` - CSS files
- `src/main/webapp/static/images` - Image files
- `pom.xml` - Maven project configuration

## Troubleshooting
- if you encounter issues, make sure to check the console logs for error messages.
- Ensure that your MySQL server is running and the database configurations are correct in 'application.properties'.
