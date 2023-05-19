# learn-spring-boot
learning springboot

java 17  
springboot 3.1.0  
tomcat 10.1.8  

this is simple demo restAPI which retrieves course details 

1) springboot provides 5 different types of logging
1. TRACE
2. DEBUG 
3. INFO 
4. WARNING 
5. ERROR
6. OFF - turn off the logging

to set the logging level go to application.properties file and set  
logging.level.org.springframework=debug

2) To create different profiles like dev, QA, stage, prod you can create following files and set the properties accordingly  
application-dev.properties  
application-qa.properties  
application-stage.properties  
application-prod.properties  

and to set the current active profile  
go to application.properties and set  
spring.profiles.active=prod
