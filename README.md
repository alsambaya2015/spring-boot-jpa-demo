# spring-boot-jpa-demo


Creating a CRUD App :
  creating a consistent and compliant REST web service requires four files, in total.

 * pom.xml
 * Application.java
 * Object.java
 * ObjectRepository.java
 
 
Requirements
 * Maven
 * JDK 8
	
Using curl

  You can see what urls are available:

   	$ curl localhost:8080

  You can view existing people objects using a similar request:

  	 $ curl localhost:8080/persons
	 
  You can add new person object (in Windows) as follows:
  
  	 $ curl -i -X POST -H "content-Type:application/json" -d " {\"firstName\":\"Paul\",\"lastName\":\"Lazlo\",\"jobTitle\":\"programmer\",\"email\":\"paul@gmail.com\"}" localhost:8080/persons
	 
