# Microservice_Day-1 Learning
#Today I started first step in microservice using Spring Boot
#I have learnt and used below set of library and framework.

#Two Microservice

    1. User Microservice : This microservice fetch personal details of user and it call contact microservice for fetching
                            contacts of that user using RestTemplate and give response back to the client. 
    2. Contact Microservice This microservice contain contact details of user.
    
#Eureka Server: Eureka Server is an application that holds the information about all client-service applications. 
                Every Micro service will register into the Eureka server and Eureka server knows all the client 
                applications running on each port and IP address.
               
#API-Gateway:   API gateway represents a single entry point into the system, providing the request routing, security, 
                protocol translation, and composition of microservices in an application.

#Resilience4J:  It is one of the Spring Cloud Circuit breaker that provides an abstraction across different circuit
                breaker implementations.
                It provides a consistent API to use in your applications.
                
#SLF4J:         This library is used to manage logging in our application for better tracking purpose in any failure. 
