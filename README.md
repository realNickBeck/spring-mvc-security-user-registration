# spring-mvc-security-user-registration
Used spring security to make a login page that connects to a mySQL Workbench database. 

Functionalities include:1) validation for all input fields using Spring-Validation
2) sign up form to register new users that provides the role of employee automatically 
3) Used Thymeleaf to parse and render the data produced by the application to template files
4) Used Hibernate/JPA to map application entities to the relational database tables 
5) Intergrated Admin, manager, and employee roles that reveal different links and web-pages based on login role
6) secure endpoints using spring security

# Dependencies Used In Spring Framework

<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>

<dependency>
  <groupId>com.mysql</groupId>
  <artifactId>mysql-connector-j</artifactId>
  <scope>runtime</scope>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-security</artifactId>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-web</artifactId>
</dependency>

<dependency>
  <groupId>org.thymeleaf.extras</groupId>
  <artifactId>thymeleaf-extras-springsecurity6</artifactId>
</dependency>

<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-validation</artifactId>
</dependency>
