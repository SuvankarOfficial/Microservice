#Microservice
This is a simple Microservice.

##Version
*Java* : 17
*Spring Boot Version (Eureka Server)* : 3.0.2
*Spring Boot Version (API Gateway)* : 3.0.2
*Spring Boot Version (User Service)* : 3.0.3-SNAPSHOT
*Spring Boot Version (Contact Service)* : 3.0.3-SNAPSHOT
*MySQL* : 8.0

Here project Eureka server act as an DNS
project API Gateway act as a bridge for other service and help them communicate
User service perform CRUD operation where as save data of Contact using feign client
Contact service perform CRUD operation using the data given by user service.

In order to work with this project 
You need to change the following:-
*In APIGateway*:-
Change the service url to the url of the eureka server running path.
*In User service*:- 
Change the service url to the url of the eureka server running path
Change the datasource url,username and password to your mysql url path, username and password respectively.
*In Contact service*:-
Change the service url to the url of the eureka server running path
Change the datasource url,username and password to your mysql url path, username and password respectively.
