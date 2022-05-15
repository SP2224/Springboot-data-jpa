Source:- https://www.javatpoint.com/spring-boot-starter-data-jpa

# Springboot-data-jpa

Step 1: Open spring Initializr https://start.spring.io/.

Step 2: Provide the Group name. We have provided com.javatpoint.

Step 3: Provide the Artifact Id. We have provided spring-boot-jpa-example.

Step 4: Add the dependencies: Spring Web, Spring Data JPA, and H2 Database.

Step 5: Click on the Generate button. When we click on the Generate button, it wraps the project in Jar file and downloads it to the local system.

<img src ="https://static.javatpoint.com/springboot/images/spring-boot-starter-data-jpa.png">

Step 6: Extract the Jar file and paste it into the STS workspace.

Step 7: Import the project folder into STS.

File -> Import -> Existing Maven Projects -> Browse -> Select the folder spring-boot-jpa-example -> Finish

It takes some time to import.

Step 8: Create a package with the name com.javatpoint.controller in the folder src/main/java.

Step 9: Create a Controller class with the name ControllerDemo in the package com.javatpoint.controller.

Step 10: Create another package with the name com.javatpoint.model in the folder src/main/java.

Step 11: Create a class with the name User in the package com.javatpoint.model.

Step 12: Open the application.properties file and configure the following things: port, enable the H2 console, datasource, and URL.

Step 13: Create a SQL file in the folder src/main/resources.

Right-click on the folder src/main/resources -> New -> File -> Provide the File name -> Finish

We have provided the file name data.sql and insert the following data into it.

Step 14: Create a folder with the name webapp in the src folder.

Step 15: Create a JSP file with the name that we have returned in the ControllerDemo. In the ControllerDemo.java, we have returned home.jsp.

Step 16: Run the SpringBootJpaExampleApplication.java file. We can see in the console that our application is successfully running on port 8085.

<img src="https://static.javatpoint.com/springboot/images/spring-boot-starter-data-jpa2.png">

Step 17: Open the browser and invoke the URL http://localhost:8085/h2-console/. It shows the Driver Class, JDBC URL that we have configured in the application.properties file, and the default User Name sa.

<img src ="https://static.javatpoint.com/springboot/images/spring-boot-starter-data-jpa3.png">

We can also test the connection by clicking on the Test Connection button. If the connection is successful, it shows a message Test Successful.

Step 18: Click on the Connect button. It shows the structure of the table userdata that we have defined in the User.java.

<img src ="https://static.javatpoint.com/springboot/images/spring-boot-starter-data-jpa4.png">

Step 19: Execute the following query to see the data that we have inserted in the data.sql file.

<img src="https://static.javatpoint.com/springboot/images/spring-boot-starter-data-jpa5.png">



