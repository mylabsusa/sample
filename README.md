
To run mongodb local from the CLI , part of mongodb.msi file. 
"C:\Program Files\MongoDB\Server\6.0\bin\mongod.exe" --dbpath="c:\mongodb\data\db"

# During installation if mongodb is installed as a service, then the above command is not needed to start the db separately. 

Connect to Mongo using mongoshell [mongosh.exe] , this has to be separately installed. 

Install mongocompass - UI client to view the mongodb and collections inside.


This uri will create db in mongo. 
spring.data.mongodb.uri=mongodb://127.0.0.1:27017/labs@home

P.S 
#use the below to connect local mongodb from a docker container and build the image.
##spring.data.mongodb.uri=mongodb://host.docker.internal:27017/labs@home


# sample references. 

Good start - https://www.mongodb.com/compatibility/spring-boot
https://www.mongodb.com/blog/post/rest-apis-with-java-spring-boot-and-mongodb

With liquibase-mongodb-  https://github.com/liquibase/liquibase-mongodb

MongoDB with crud operations - https://examples.javacodegeeks.com/java-development/enterprise-java/spring/mvc/spring-mvc-crud-using-mongodb-tutorial/

MongoDB with REST API - https://plainenglish.io/blog/building-a-rest-api-using-mongodb-and-spring-boot-c50b18ee6efa
 https://medium.com/javarevisited/building-a-rest-service-with-spring-boot-and-mongodb-part-1-2de01e4f434d
 
 https://www.javaguides.net/2019/12/spring-boot-crud-rest-api-mongodb-maven-example-tutorial.html
 
 
 https://www.mongodb.com/compatibility/docker
