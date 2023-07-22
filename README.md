# Microservice#
This is a simple Microservice.

## Version
* Java : 17
* Spring Boot Version (Eureka Server) : 3.0.2
* Spring Boot Version (API Gateway) : 3.0.2
* Spring Boot Version (User Service) : 3.0.3-SNAPSHOT
* MySQL : 8.0

Here project Eureka server act as an DNS
project API Gateway act as a bridge for other service and help them communicate
User service perform CRUD operation

In order to work with this project 
You need to change the following:-

* In APIGateway :-
Change the service url to the url of the eureka server running path.

* In User service :- 
Change the service url to the url of the eureka server running path
Change the datasource url,username and password to your mysql url path, username and password respectively.

### In order to run this project
1. Run the Eureka Server
2. Copy the path of server and enter it in APIGateway and User Service.
3. Run APIGateway 
4. Run MySQL Server
5. Enter the path of MySQL server in User Service
6. Run User Service 
