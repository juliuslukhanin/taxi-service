# :taxi: Taxi-service :taxi:
### Project Description:
`A simple web application that supports authentication, registration, and basic CRUD operations.`

### Features:
- registration like a driver
- authentication like a driver
- creat/update/remove a car
- creat/update/remove a driver
- creat/update/remove a manufactures
- display list of all car
- display list of all driver
- display list of all manufactures
- display list of all cars in the driver

### Project based on 3-layer architecture:
1. Presentation layer
2. Business layer
3. Data layer

### Used technologies:
- Java 11
- JDBC
- MySQL 8.0.29
- Servlet 4.0.1
- JSP
- JSTL 1.2
- HTML, CSS
- Maven 3.8.0
- TomCat 9.0.50

### How to run this project:
1. Install MySQL and Apache Tomcat
2. Run script from the resources/init_db.sql file in the MySQL Workbench
3. Configure Tomcat (application context must be "/")
4. Set your URL, USERNAME, PASSWORD, JDBC_DRIVER in /util/ConnectionUtil.java
5. Run