# :taxi: ***Taxi Service*** :taxi:
___
### :pushpin: ***Project description*** :pushpin:
***Web-application that supports driver authentication, registration and other CRUD operations with cars, manufacturers, drivers***
___
### :bookmark: ***Features:*** :bookmark:
+ :pencil2: ***register a driver***
+ :unlock: ***log in/out***
+ :notebook: ***create/read/update a car***   
+ :notebook: ***create/read/update a manufacturer***    
+ :notebook: ***create/read/update a driver***    
+ :mag_right: ***display list of all cars***     
+ :mag_right: ***display list of all manufacturers*** 
+ :mag_right: ***display list of all drivers*** 
___
### :open_file_folder: ***Structure:*** :open_file_folder:
+ ***Controller - accepts requests from the user, passes them to the service layer and returns jsp pages in response***
+ ***Service - accepts requests from the controller, passes them to the DAO layer and performs all business logic***
+ ***DAO - accepts requests from the service, passes them to the DB and executes all sql queries***
___
### :page_with_curl: ***Technologies:*** :page_with_curl:
+ ***[Tomcat 9.0.50](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)***
+ ***[Maven](https://maven.apache.org/download.cgi)***
+ ***[MySQL](https://dev.mysql.com/downloads/installer/)***
+ ***JDBC***
+ ***[Java 11](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)***
+ ***JSP***
+ ***JSTL***
___
### :question: ***How to run this project: :question:***    
- [x] ***Fork this project to your repository***    
- [x] ***Press "Code" and choose HTTPS or SSH url to clone the project***    
- [x] ***Create new project from Version Control and write this url***    
- [x] ***Write your properties to ConnectionUtil class***    
```java
    private static final String URL = "DB_URL";
    private static final String USERNAME = "USERNAME";
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
- [x] ***Create DB, for this use init_db.sql***    
- [x] ***Install Tomcat and configure it in your IDEA***    
- [x] ***Run the project***    
