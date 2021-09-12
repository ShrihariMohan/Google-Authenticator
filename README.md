# Google Authenticator
This is a web app developed using Angular + Spring Boot + Mysql


https://user-images.githubusercontent.com/60439461/132974509-89e9c454-5ca6-4d5b-8a11-1146e2f71e25.mp4


## Features 
- 2 step authentication
- angular v 12

## Start the client
Go to the Client folder and run the following commands

- ``` npm install ```
- ``` ng serve ```
Now the client will be live on http://localhost:4200

## Start the server
I am using Intellij Idea community version that helps me start the spring boot server by just running the application.
### Before starting the application
- Create a file called application.properties in the following path BackEnd/src/main/resources/application.properties
- Then add the following fields with your database name and tables

```java
spring.datasource.url = jdbc:mysql://localhost:3306/DATABASE_NAME 
spring.datasource.username = USERNAME
spring.datasource.password= PASSWORD
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect
server.port=9000
jwt.secret=YOUR_SECRET_KEY
```
### The final result should be something like this , file structure and fields
![image](https://user-images.githubusercontent.com/60439461/132976500-290b2d14-1870-4e38-9c74-daee5526e9c0.png)

