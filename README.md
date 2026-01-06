# ecommerce-microservices
* When I  started to build an ecommerce application, 
* I came to know it is good to build an ecommerce application with  a microservice architecture. 
* Before knowing what is  microservices , A doubt raised in my mind that is 

## Why microservices? 
* Microservices are used to build large application as small , independent ,loosely coupled services 
    enabling faster development , easier scaling , better fault isolation ...etc.
*  Microservices are used in e-commerce for their superior **Scalability,** **Resiliance,** **And** **Agility.**
* Allowing the independent scaling of services like search , payment , order based on the peak timings. 
* This architecture supports agile development with small dedicated teams , better fault isolation 
 and technology flexibility ultimately improving customer experience and future proofing the platform. 


## How Microservices communicate with each other? 
* Microservices communicate with each other using two primary architectural styles: Synchronous and Asynchronous.
*  In a distributed system, services act as independent processes and must interact over a network using well-defined APIs or Events.
   ## 1. Synchronous Communication (Request/Response)
    * REST API's (http / https). 
    * GRPC (http/2 and binary serialization for boosting the performance ). 
    * GraphQL (allow the data what is needed ). 

   ## 2. Asynchronous Communication (Event-Driven)
    * Message Queues 
    * Publish/Subscribe
