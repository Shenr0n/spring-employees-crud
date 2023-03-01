# Employee Management Web Application

* Real-time web application to manage employee details and perform CRUD operations based on user’s role/authorization. Uses Java 8 with Spring Boot, Spring Data Java Persistence API, Maven, MySQL database, and Thymeleaf to create Web UI.


## Tech-stack
* `Eclipse` - Eclipse is an integrated development environment.  [Eclipse Website](https://www.eclipse.org/downloads/)
* `MySQL` - MySQL is an open-source relational database management system. [MySQL Website](https://www.mysql.com/downloads/)
* `Spring` - Spring Boot is a tool that makes developing web application and microservices with Spring Framework faster and easier. [Spring initializr](https://start.spring.io/)
* `Java 8` - [Java Website](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)
* `Thymeleaf` - Thymeleaf is a modern server-side Java template engine for both web and standalone environments. [Thymeleaf website](https://www.thymeleaf.org/documentation.html)
* `Maven` - Apache Maven is a software project management and comprehension tool. [Maven website](https://maven.apache.org/)

## How to run the project?

* Install Eclipse, MySQL, Java 8 SDK and complete their configurations.
* Create a MySQL local connection and set the appropriate username and password. 
* In MySQL, after logging in, click on File -> Open SQL Scripts. Locate the *'sql-scripts'* folder in the project and execute both scripts. This will create the necessary schemas for the project with some initial sample values.
* Read the SQL script and its comments for the different users, sample passwords and their roles. Admin can perform CREATE, READ, UPDATE and DELETE. Manager can CREATE, READ and UPDATE. Employee can CREATE and READ.

* Open Eclipse. Click on File -> Import -> Existing Maven Project -> Browse Root Directory. Locate the project folder and click Finish.
* First open the *'application.properties'* file and update the MySQL connection username and password.
* To import all the required dependencies, right click on the project -> Maven -> Update Project. Then right click on project and click Refresh.

* Inside Eclipse, Locate the *'src/main/java/com.shenron.springboot.thymeleafdemo/'* folder in the project. Right click on *'ThymeleafdemoApplication.java'* -> Run as Java Application.
* After the application is started, open any web browser and write localhost:8080/employees in the address bar. Login with any of the user roles from the schema and perform the CRUD operations as necessary.
