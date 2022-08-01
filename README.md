# taxi-service
### Project Description
This is a simple web-application for managing taxi park. It represents work of such taxi service and has next functions:

- Add user
- Add manufacturer of car
- Add car using manufacturer
- Show all users
- Show all cars of current user
- Show all manufacturers
- Show all cars with attached drivers
- Delete users 
- Delete manufacturers
- Delete cars
- Change attached drivers for car

### Project represents 3-layer architecture:

1. Presentation layer 
2. Business layer
3. Data layer 

### Technologies used in project

- Java 11
- Apache tomcat 9.0.64
- MySQL 8.0.29
- Servlet API 4.0.1
- JDBC
- JSTL 1.2
- JSP
- HTML, CSS

### How to install and configure

1. Install Tomcat 9
2. Install MySQL
3. Configure Tomcat(application context must be "/")
4. Create schema using init_db.sql
5. Set environment variables: DATABASE_TAXI_URL, DATABASE_TAXI_USER, DATABASE_TAXI_PASSWORD or change them in ConnectionUtil.java
6. Run 

